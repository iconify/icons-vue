<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivpjwx_1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ivpjwx_1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mail-empty" /></template>
