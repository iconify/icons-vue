<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/femfy8bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="femfy8bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-open" /></template>
