<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n912f000d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n912f000d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:laptop-windows" /></template>
