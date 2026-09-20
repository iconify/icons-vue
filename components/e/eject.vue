<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqy5knu7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vqy5knu7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:eject" /></template>
