<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2bl_ob4g.css';
import '../../css/m/m0pn6bzto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2bl_ob4g"/><path class="m0pn6bzto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-bold-duotone" /></template>
