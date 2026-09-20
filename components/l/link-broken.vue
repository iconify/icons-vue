<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2rtvsbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="x2rtvsbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:link-broken" /></template>
