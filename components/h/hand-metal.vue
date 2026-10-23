<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2pzlm6fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2pzlm6fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hand-metal" /></template>
