<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnhqg0bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnhqg0bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:easy-in-out-line" /></template>
