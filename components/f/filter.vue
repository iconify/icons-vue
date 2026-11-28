<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gei0--jlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gei0--jlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:filter" /></template>
