<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idh17h92l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="idh17h92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:base-ui-dark" /></template>
