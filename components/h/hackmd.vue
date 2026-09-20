<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osy670bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osy670bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hackmd" /></template>
