<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv1pozbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xv1pozbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anti-clockwise-outline" /></template>
