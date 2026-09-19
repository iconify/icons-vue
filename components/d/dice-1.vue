<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zckc6lblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="zckc6lblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:dice-1" /></template>
