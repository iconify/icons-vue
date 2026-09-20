<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r470qoc2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r470qoc2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-on-90" /></template>
