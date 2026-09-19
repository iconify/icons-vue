<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_wlcnbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_wlcnbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:equalizer2" /></template>
