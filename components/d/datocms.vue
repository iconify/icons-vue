<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq4ywbbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq4ywbbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:datocms" /></template>
