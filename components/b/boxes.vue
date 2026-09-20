<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgn1o77jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xgn1o77jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:boxes" /></template>
