<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji7ws2beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji7ws2beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:information-off-line" /></template>
