<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tunn1-bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tunn1-bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:droplet-half-solid" /></template>
