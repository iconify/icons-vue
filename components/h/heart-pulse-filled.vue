<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wexh7077m.css';
import '../../css/r/r1d07kbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wexh7077m"/><path class="r1d07kbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-pulse-filled" /></template>
