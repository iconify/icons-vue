<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5f9s_k4f.css';
import '../../css/o/oc7x2x87v.css';
import '../../css/k/kcpt-5ssg.css';
import '../../css/h/hoiq_la6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q5f9s_k4f"/><path class="oc7x2x87v"/><path class="kcpt-5ssg"/><path class="hoiq_la6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cybersecurity-20-bold" /></template>
