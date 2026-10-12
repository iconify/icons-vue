<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwf-ck3ci.css';
import '../../css/k/kj6dhhbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwf-ck3ci"/><path class="kj6dhhbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-mask-20-bold" /></template>
