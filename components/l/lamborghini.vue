<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1-1-_to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1-1-_to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lamborghini" /></template>
