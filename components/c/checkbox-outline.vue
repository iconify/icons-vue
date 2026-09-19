<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_cpnh_xd.css';
import '../../css/h/hqrdqe__q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_cpnh_xd"/><rect class="hqrdqe__q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkbox-outline" /></template>
