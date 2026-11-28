<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpazoccdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpazoccdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-check" /></template>
