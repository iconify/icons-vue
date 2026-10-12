<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzi4bo-8z.css';
import '../../css/s/seg7ew6ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzi4bo-8z"/><path class="seg7ew6ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:image-fill-20" /></template>
