<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmdh8w37g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="lmdh8w37g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:candy-stick" /></template>
