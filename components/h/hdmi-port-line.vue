<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-fmnzr3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-fmnzr3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hdmi-port-line" /></template>
