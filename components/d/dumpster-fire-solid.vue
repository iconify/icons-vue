<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhnt1hz_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vhnt1hz_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dumpster-fire-solid" /></template>
