<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcd4a1t7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcd4a1t7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:blackberry-logo-bold" /></template>
