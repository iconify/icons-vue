<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzoe07b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzoe07b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hand-right" /></template>
