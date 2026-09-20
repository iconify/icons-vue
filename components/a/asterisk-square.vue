<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_cs__10r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_cs__10r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:asterisk-square" /></template>
