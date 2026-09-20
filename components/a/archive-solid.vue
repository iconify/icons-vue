<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu4d6vbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wu4d6vbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:archive-solid" /></template>
