<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5h8h31za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":512};
const content = `<path class="q5h8h31za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bluetooth-setting" /></template>
