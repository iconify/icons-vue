<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk2jde1-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2jde1-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-square-right-filled" /></template>
