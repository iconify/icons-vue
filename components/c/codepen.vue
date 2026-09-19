<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kun4g3fhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kun4g3fhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:codepen" /></template>
