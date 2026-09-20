<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6g11fwan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="e6g11fwan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark-f" /></template>
