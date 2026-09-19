<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz2l__b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zz2l__b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:eject" /></template>
