<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi1_wzkmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hi1_wzkmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bell" /></template>
