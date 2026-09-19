<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my-kglbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my-kglbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-resize" /></template>
