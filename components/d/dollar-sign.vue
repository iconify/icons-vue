<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sog00tb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sog00tb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dollar-sign" /></template>
