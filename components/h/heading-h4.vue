<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f02ft-m9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f02ft-m9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heading-h4" /></template>
