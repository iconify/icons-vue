<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz09zhb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qz09zhb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-up-20" /></template>
