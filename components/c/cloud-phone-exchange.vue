<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4-u_bchg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4-u_bchg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cloud-phone-exchange" /></template>
