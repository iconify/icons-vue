<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh078gb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="rh078gb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cloud-down" /></template>
