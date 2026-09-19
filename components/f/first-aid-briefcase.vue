<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2msgnz-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="q2msgnz-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:first-aid-briefcase" /></template>
