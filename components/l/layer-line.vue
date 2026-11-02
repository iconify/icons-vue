<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjpvtnbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjpvtnbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layer-line" /></template>
