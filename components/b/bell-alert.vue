<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh2cwfbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh2cwfbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bell-alert" /></template>
