<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt3g05bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lt3g05bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:colon" /></template>
