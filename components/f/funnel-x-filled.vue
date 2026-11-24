<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy_akccwx.css';
import '../../css/k/kohszfbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy_akccwx"/><path class="kohszfbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:funnel-x-filled" /></template>
