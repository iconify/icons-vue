<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j14ur1b8a.css';
import '../../css/y/ybf22hb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j14ur1b8a"/><path class="ybf22hb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:counter-analytics" /></template>
