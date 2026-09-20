<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_b_9cx1c.css';
import '../../css/i/iejop6bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_b_9cx1c"/><path class="iejop6bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alibabacloud" /></template>
