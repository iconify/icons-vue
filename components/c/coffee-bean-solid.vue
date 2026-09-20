<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd6li47sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wd6li47sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coffee-bean-solid" /></template>
