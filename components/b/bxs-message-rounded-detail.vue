<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1lcx54am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1lcx54am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-rounded-detail" /></template>
