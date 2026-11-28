<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiw3j3-js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiw3j3-js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:id-card-lock" /></template>
