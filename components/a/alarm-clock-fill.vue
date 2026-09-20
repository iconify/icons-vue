<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_xah05r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_xah05r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:alarm-clock-fill" /></template>
