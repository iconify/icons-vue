<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc5k_m5oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc5k_m5oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:brain" /></template>
