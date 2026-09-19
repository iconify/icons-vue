<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz3lbxnkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz3lbxnkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:code" /></template>
