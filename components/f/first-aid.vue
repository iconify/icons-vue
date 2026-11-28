<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee-sbeb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-sbeb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:first-aid" /></template>
