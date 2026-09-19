<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_o7p0b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_o7p0b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-blind-open" /></template>
