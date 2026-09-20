<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-2mw_ycm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-2mw_ycm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eight-sleep" /></template>
