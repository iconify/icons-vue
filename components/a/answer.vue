<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wassgy4fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wassgy4fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:answer" /></template>
