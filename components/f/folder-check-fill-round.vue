<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psjqb7bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psjqb7bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-check-fill-round" /></template>
