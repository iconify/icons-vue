<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blu3__1ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="blu3__1ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leak-20" /></template>
