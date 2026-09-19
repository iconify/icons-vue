<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5-ql04qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1408};
const content = `<path class="h5-ql04qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:folder-open-o" /></template>
