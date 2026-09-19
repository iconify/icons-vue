<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb_xwzbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="pb_xwzbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-indent-decrease" /></template>
