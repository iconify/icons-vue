<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/allq33zyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="allq33zyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-blank-outline" /></template>
