<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aev2ndtkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aev2ndtkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-upload-x" /></template>
