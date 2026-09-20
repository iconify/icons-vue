<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edex25bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edex25bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bulb-filled" /></template>
