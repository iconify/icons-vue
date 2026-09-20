<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv6-mbbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv6-mbbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:hospital-symbol" /></template>
