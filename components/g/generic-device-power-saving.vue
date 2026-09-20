<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfektw75g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfektw75g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-power-saving" /></template>
