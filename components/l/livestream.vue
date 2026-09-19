<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2hylacvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="x2hylacvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:livestream" /></template>
