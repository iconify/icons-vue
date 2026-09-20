<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luqxxebuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luqxxebuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cloudy-night-filled" /></template>
