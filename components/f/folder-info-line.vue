<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bus69jdjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bus69jdjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-info-line" /></template>
