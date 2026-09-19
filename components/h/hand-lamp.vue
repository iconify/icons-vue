<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5wdz0b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h5wdz0b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hand-lamp" /></template>
