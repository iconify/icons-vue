<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os60q4b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os60q4b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-hung-3-alt" /></template>
