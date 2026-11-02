<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmv87z_kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmv87z_kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:live-location-line" /></template>
