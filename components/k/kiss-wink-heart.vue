<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrk10cbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":512};
const content = `<path class="xrk10cbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:kiss-wink-heart" /></template>
