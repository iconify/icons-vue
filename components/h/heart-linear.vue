<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc4zhgevm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc4zhgevm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-linear" /></template>
