<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbalmob2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbalmob2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:just-eat" /></template>
