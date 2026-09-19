<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh1w0u0lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh1w0u0lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:econt" /></template>
