<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcov7on7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="vcov7on7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:battery-empty" /></template>
