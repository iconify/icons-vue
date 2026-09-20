<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reh36qgiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reh36qgiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:esea" /></template>
