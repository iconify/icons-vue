<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjs9i0baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fjs9i0baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:gate" /></template>
