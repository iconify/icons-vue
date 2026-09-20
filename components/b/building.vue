<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2zzebsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="co2zzebsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:building" /></template>
