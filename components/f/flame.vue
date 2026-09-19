<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm8xffb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zm8xffb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:flame" /></template>
