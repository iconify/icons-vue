<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyvt1zbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvt1zbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulbs-filament" /></template>
