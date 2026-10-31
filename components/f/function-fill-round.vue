<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz6ri2bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz6ri2bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:function-fill-round" /></template>
