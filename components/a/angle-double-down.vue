<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8fp8b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa8fp8b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:angle-double-down" /></template>
