<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlzsimbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlzsimbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-3-line" /></template>
