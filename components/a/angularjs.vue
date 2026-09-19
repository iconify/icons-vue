<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3tp0ef-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="p3tp0ef-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angularjs" /></template>
