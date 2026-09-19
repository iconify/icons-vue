<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_kgj_bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_kgj_bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-add-01" /></template>
