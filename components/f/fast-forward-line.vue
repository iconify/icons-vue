<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxcp3cjpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxcp3cjpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fast-forward-line" /></template>
