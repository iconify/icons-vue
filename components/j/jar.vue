<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_k5bkbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_k5bkbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:jar" /></template>
