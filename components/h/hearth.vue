<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy1aaaclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy1aaaclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hearth" /></template>
