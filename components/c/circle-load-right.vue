<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atktmkbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="atktmkbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-load-right" /></template>
