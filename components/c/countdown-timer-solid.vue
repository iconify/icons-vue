<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipj3-xb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipj3-xb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:countdown-timer-solid" /></template>
