<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chr3v_s-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chr3v_s-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clarifai" /></template>
