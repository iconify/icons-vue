<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmds795_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmds795_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazondocumentdb" /></template>
