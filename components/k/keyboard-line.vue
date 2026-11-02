<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifbk99bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifbk99bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-line" /></template>
