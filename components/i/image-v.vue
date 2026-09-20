<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtgv8-bzl.css';
import '../../css/v/v4bnoj-6z.css';
import '../../css/i/iturx2siu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtgv8-bzl"/><path class="v4bnoj-6z"/><path class="iturx2siu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:image-v" /></template>
