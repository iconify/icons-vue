<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4uwu8bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4uwu8bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jetpack-compose" /></template>
