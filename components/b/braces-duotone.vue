<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1j71ccor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1j71ccor primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:braces-duotone" /></template>
