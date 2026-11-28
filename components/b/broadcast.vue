<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae5vnnbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae5vnnbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:broadcast" /></template>
