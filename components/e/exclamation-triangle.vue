<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms1ustbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms1ustbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:exclamation-triangle" /></template>
