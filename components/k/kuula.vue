<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ponnvm25y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ponnvm25y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kuula" /></template>
