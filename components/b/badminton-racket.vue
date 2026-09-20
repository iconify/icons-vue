<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjti-ug9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cjti-ug9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badminton-racket" /></template>
