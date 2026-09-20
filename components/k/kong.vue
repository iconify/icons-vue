<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nug6dobco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nug6dobco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kong" /></template>
