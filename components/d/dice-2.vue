<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlm1qqb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="rlm1qqb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:dice-2" /></template>
