<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4_udjxz.css';
import '../../css/i/i3y9_vb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti4_udjxz"/><path class="i3y9_vb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-days-20" /></template>
