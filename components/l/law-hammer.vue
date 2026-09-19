<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwy89e47i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="iwy89e47i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:law-hammer" /></template>
