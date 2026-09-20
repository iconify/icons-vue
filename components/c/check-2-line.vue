<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh040mbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh040mbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-2-line" /></template>
