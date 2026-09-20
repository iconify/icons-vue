<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awcdb7b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awcdb7b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fluke" /></template>
