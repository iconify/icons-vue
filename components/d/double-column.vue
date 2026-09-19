<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg9io8bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hg9io8bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-column" /></template>
