<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqv21hmdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqv21hmdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-70" /></template>
