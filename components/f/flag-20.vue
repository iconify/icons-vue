<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y69yz0bvp.css';
import '../../css/b/b9tupzbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y69yz0bvp"/><path class="b9tupzbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-20" /></template>
