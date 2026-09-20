<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp9_jbb1j.css';
import '../../css/p/pnjqzgbmt.css';
import '../../css/h/hlqjywb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wp9_jbb1j"/><path class="pnjqzgbmt"/><path class="hlqjywb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-artboard-shapes" /></template>
