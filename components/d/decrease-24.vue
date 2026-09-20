<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4qmo_swz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4qmo_swz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:decrease-24" /></template>
