<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ljxq3-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ljxq3-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anta" /></template>
