<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doip9tbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-8,"top":-5};
const content = `<path class="doip9tbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-right" /></template>
