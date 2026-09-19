<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghokk2bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghokk2bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-paus" /></template>
