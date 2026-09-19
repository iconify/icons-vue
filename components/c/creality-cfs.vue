<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owtso8eld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owtso8eld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:creality-cfs" /></template>
