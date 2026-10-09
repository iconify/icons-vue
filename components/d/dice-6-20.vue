<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxp0_ibgn.css';
import '../../css/v/v3yw67n4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp0_ibgn"/><path class="v3yw67n4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-6-20" /></template>
