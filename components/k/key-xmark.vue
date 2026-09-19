<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp8sdbcdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp8sdbcdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:key-xmark" /></template>
