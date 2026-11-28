<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qui-vigal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qui-vigal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:acorn" /></template>
