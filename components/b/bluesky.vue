<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmvvp4bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":226};
const content = `<path class="vmvvp4bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bluesky" /></template>
