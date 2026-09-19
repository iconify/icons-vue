<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0c1x_brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h0c1x_brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flowernew" /></template>
