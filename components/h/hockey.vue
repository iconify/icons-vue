<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx3a-kbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xx3a-kbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hockey" /></template>
