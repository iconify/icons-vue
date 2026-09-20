<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf3q7_mjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf3q7_mjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horseshoe" /></template>
