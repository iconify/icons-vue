<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phsxt4blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phsxt4blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bitcoin" /></template>
