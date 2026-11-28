<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa9u4gmpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9u4gmpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cable-car-clock" /></template>
