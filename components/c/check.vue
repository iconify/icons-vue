<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htbxum14x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="htbxum14x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:check" /></template>
