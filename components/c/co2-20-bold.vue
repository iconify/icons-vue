<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifignib1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifignib1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-20-bold" /></template>
