<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5z8iib0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5z8iib0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:br1" /></template>
