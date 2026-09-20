<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isjll-ize.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isjll-ize"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-40" /></template>
