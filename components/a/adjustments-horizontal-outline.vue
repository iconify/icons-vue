<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plo6q25eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plo6q25eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:adjustments-horizontal-outline" /></template>
