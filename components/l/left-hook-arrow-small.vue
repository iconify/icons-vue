<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m621oab_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m621oab_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-hook-arrow-small" /></template>
