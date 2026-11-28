<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf30up41c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf30up41c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:archive-lock" /></template>
