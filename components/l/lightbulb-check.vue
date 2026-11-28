<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbv90cc1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbv90cc1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lightbulb-check" /></template>
