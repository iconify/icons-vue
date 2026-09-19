<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtmqx4blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtmqx4blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-fair" /></template>
