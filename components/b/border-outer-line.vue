<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewv6nub2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewv6nub2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-outer-line" /></template>
