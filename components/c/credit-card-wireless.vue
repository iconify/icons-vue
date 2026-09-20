<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4z3p6btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4z3p6btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-wireless" /></template>
