<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jks7n9fgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="jks7n9fgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:edge" /></template>
