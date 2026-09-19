<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofbd67oxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="ofbd67oxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angelist" /></template>
