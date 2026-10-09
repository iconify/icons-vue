<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waz_2hbmd.css';
import '../../css/e/eyzw0tyws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="waz_2hbmd"/><path class="eyzw0tyws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grass-20" /></template>
