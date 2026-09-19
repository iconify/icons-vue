<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkb-y5lvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkb-y5lvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-left-box-outline" /></template>
