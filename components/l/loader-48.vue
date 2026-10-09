<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvt_43blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvt_43blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loader-48" /></template>
