<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lybmi-wnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lybmi-wnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:achievement-award" /></template>
