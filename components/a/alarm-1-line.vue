<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxou2p47l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxou2p47l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-1-line" /></template>
