<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqf38tbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="sqf38tbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-fill" /></template>
