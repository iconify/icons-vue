<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwo6jpb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cwo6jpb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:docker" /></template>
