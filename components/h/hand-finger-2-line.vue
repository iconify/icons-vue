<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skl5xx2af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skl5xx2af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-finger-2-line" /></template>
