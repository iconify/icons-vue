<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltp815bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ltp815bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:docker" /></template>
