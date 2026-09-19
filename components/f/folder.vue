<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3zho7bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3zho7bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:folder" /></template>
