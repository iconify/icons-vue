<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8x25ojnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w8x25ojnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:c-sharp-outline" /></template>
