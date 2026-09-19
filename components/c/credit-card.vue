<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krzg23dcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="krzg23dcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:credit-card" /></template>
