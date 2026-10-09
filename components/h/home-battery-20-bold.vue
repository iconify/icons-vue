<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fckik_nux.css';
import '../../css/r/ryvp9vm2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fckik_nux"/><path class="ryvp9vm2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-20-bold" /></template>
