<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy8doab7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hy8doab7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:magnifier" /></template>
