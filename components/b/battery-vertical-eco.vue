<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0x3zvd3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0x3zvd3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-eco" /></template>
