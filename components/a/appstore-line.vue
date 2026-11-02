<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc7c0z81x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7c0z81x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:appstore-line" /></template>
