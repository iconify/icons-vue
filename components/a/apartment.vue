<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1-5195me.css';
import '../../css/w/wyynnt73k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h1-5195me"/><path class="wyynnt73k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:apartment" /></template>
