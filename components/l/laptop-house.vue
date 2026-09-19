<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc-pl27ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="cc-pl27ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:laptop-house" /></template>
