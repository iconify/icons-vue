<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z20mj7wwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z20mj7wwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:equalizer" /></template>
