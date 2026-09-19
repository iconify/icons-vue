<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj_u1q2qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yj_u1q2qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dashboard-26" /></template>
