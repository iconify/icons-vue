<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vylacab7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vylacab7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-rounded-add" /></template>
