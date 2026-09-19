<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsvpfcb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsvpfcb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-lamp-round" /></template>
