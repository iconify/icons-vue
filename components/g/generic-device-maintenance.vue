<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zia8m971p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zia8m971p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-maintenance" /></template>
