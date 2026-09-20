<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn9e5mbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn9e5mbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-inbound" /></template>
