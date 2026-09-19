<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4gqgybhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="k4gqgybhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:eye-drop" /></template>
