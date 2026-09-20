<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtcxr4dzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtcxr4dzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:icon" /></template>
