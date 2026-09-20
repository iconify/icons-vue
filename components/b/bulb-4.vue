<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr_rigy-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="hr_rigy-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bulb-4" /></template>
