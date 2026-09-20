<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6a_1ssme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6a_1ssme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-down-circle-fill" /></template>
