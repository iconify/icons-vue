<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mus218bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mus218bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bracket-square-solid" /></template>
