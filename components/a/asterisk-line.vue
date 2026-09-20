<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkq-vrs-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkq-vrs-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:asterisk-line" /></template>
