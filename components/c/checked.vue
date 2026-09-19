<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6tv7ib_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="j6tv7ib_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:checked" /></template>
