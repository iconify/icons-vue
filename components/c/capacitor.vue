<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23zuob8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path paint-order="fill markers stroke" class="q23zuob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:capacitor" /></template>
