<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk-v9cckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="pk-v9cckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bread" /></template>
