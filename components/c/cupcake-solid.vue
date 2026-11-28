<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uufo2obkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uufo2obkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cupcake-solid" /></template>
