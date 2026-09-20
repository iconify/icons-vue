<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3mk329u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3mk329u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-u-box" /></template>
