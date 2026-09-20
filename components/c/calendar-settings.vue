<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma32ezb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ma32ezb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:calendar-settings" /></template>
