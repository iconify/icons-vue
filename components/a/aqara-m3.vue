<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug9i3c-fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug9i3c-fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-m3" /></template>
