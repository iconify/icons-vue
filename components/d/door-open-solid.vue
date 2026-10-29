<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo-2b4bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-2b4bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:door-open-solid" /></template>
