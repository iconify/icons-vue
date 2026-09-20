<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35yy7v4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f35yy7v4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ghost" /></template>
