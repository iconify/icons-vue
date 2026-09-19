<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyj7cpbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gyj7cpbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:keyboard" /></template>
