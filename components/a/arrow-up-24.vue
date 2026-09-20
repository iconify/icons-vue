<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq64mymnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq64mymnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-up-24" /></template>
