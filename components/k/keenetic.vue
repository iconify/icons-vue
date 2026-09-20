<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgy70ubrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgy70ubrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:keenetic" /></template>
