<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5bcwbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un5bcwbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fandango" /></template>
