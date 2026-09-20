<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivu86bhxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ivu86bhxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:laughing-face-in-circle" /></template>
