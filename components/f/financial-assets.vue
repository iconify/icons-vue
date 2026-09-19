<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2k3qxhyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n2k3qxhyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:financial-assets" /></template>
