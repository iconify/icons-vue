<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j50656bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":364,"height":56};
const content = `<path class="j50656bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:character-ai" /></template>
