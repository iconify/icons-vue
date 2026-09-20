<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/palu_ab3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="palu_ab3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brick-wall-fill" /></template>
