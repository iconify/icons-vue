<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed9oapbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed9oapbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-floodlight" /></template>
