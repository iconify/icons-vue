<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as6zalapf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as6zalapf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ard" /></template>
