<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mehhvibxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mehhvibxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database-arrow-down" /></template>
