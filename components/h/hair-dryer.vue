<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkcm9o7dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkcm9o7dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hair-dryer" /></template>
