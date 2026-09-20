<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4hsracca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s4hsracca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:love2d" /></template>
