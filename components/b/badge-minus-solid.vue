<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_el_48wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_el_48wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-minus-solid" /></template>
