<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxdiohepy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxdiohepy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:dimond-alt-light" /></template>
