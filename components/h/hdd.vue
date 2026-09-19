<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syrwku2zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="syrwku2zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hdd" /></template>
