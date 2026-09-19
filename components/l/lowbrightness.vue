<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uddk3r85r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uddk3r85r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lowbrightness" /></template>
