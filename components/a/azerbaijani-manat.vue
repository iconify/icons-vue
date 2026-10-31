<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l18-8umqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l18-8umqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:azerbaijani-manat" /></template>
