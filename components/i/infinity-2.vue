<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7gtf23ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="p7gtf23ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:infinity-2" /></template>
