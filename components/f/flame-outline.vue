<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmeb5jr_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmeb5jr_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flame-outline" /></template>
