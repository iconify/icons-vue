<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftt6qlmpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftt6qlmpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:curl" /></template>
