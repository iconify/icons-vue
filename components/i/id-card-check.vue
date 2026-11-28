<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiqj8cb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiqj8cb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:id-card-check" /></template>
