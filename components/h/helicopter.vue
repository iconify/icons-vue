<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebs0_ubnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebs0_ubnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:helicopter" /></template>
