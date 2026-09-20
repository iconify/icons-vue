<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut988i6ey.css';
import '../../css/b/bvhpy4bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut988i6ey"/><path class="bvhpy4bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-ie" /></template>
