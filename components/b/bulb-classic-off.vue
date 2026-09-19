<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsruj0bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsruj0bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-classic-off" /></template>
