<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljw_3tj1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ljw_3tj1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kserve-dark" /></template>
