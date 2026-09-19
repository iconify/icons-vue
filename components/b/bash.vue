<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drrvdkb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drrvdkb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bash" /></template>
