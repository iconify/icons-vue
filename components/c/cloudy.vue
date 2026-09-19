<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9wmphbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="v9wmphbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cloudy" /></template>
