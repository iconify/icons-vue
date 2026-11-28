<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqnh7lc1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqnh7lc1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:inbox-arrow-right" /></template>
