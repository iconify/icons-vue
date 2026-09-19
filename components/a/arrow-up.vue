<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw292dx7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw292dx7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-up" /></template>
