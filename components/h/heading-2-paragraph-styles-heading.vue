<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zydi_fb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zydi_fb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heading-2-paragraph-styles-heading" /></template>
