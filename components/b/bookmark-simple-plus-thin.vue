<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj8oc32ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nj8oc32ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-plus-thin" /></template>
