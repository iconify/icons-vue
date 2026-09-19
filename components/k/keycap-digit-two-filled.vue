<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk3hwbdsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kk3hwbdsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-two-filled" /></template>
