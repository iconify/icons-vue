<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbt1owbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbt1owbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:inpatient-24px" /></template>
