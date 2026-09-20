<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_-c2-bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_-c2-bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:italic-circle-filled" /></template>
