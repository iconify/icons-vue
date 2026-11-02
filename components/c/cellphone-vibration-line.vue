<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og00ut_0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og00ut_0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-vibration-line" /></template>
