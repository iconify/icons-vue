<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebj6rvb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="ebj6rvb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:linux" /></template>
