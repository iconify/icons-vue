<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aegej5mnd.css';
import '../../css/o/oyd37-buh.css';
import '../../css/n/nryc-8-0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aegej5mnd"/><path class="oyd37-buh"/><path class="nryc-8-0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cnc-machine-20-bold" /></template>
