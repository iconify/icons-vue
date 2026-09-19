<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujyzd5b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ujyzd5b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:dribbble" /></template>
