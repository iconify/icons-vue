<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn64yx6un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn64yx6un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:import-export" /></template>
