<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoj2oy0oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj2oy0oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-u-box-outline" /></template>
