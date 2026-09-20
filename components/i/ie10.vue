<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4a4zcb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r4a4zcb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ie10" /></template>
