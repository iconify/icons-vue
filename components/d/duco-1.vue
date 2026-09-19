<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz1m15bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz1m15bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duco-1" /></template>
