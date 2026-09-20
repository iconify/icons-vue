<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df2g-2x7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df2g-2x7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-line" /></template>
