<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp-an9b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp-an9b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-1-line" /></template>
