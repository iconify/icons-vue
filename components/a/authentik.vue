<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq4i1lqpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq4i1lqpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:authentik" /></template>
