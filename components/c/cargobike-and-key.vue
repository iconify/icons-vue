<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1l5dhiww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v1l5dhiww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-key" /></template>
