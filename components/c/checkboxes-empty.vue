<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjyxj_bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xjyxj_bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkboxes-empty" /></template>
