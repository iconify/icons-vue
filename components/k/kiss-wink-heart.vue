<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db2a-lbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="db2a-lbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:kiss-wink-heart" /></template>
