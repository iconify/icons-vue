<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzw-toepp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzw-toepp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:libra-line" /></template>
