<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_jglacoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_jglacoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:air-india" /></template>
