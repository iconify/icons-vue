<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3n6gqc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n6gqc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:drive-cage" /></template>
