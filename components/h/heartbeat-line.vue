<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxx8nlbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxx8nlbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-line" /></template>
