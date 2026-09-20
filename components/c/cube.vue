<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6w24rbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6w24rbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cube" /></template>
