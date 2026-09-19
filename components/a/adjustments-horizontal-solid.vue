<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_rj_2ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1_rj_2ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:adjustments-horizontal-solid" /></template>
