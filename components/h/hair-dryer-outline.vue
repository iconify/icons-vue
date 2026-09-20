<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw9ii1w0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw9ii1w0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hair-dryer-outline" /></template>
