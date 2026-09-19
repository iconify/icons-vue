<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxt_ksb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxt_ksb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:filter" /></template>
