<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unrze375k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unrze375k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:heart-filled-24" /></template>
