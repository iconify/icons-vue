<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izuh8ib-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izuh8ib-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-bollard-3-off" /></template>
