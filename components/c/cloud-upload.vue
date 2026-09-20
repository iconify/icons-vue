<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy1mwtb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hy1mwtb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:cloud-upload" /></template>
