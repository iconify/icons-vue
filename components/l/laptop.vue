<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpo11j3ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="cpo11j3ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:laptop" /></template>
