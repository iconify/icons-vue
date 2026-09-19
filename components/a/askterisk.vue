<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8kcn7bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="g8kcn7bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:askterisk" /></template>
