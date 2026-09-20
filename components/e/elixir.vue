<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_fy9wzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_fy9wzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:elixir" /></template>
