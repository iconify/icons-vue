<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg5j54blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="fg5j54blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bug" /></template>
