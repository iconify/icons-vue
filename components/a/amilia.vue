<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9oblrb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r9oblrb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:amilia" /></template>
