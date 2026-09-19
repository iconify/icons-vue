<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz2f2xxxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz2f2xxxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:glasses-alt" /></template>
