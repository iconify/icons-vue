<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7m_sy6ir.css';
import '../../css/q/qmmje9uau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7m_sy6ir"/><path class="qmmje9uau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioner-20-bold" /></template>
