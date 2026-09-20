<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/f/f3rx7t.css';
import '../../css/t/txuwiv.css';
import '../../css/y/yp-liy.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c f3rx7t"/><path class="a0m25c txuwiv"/><path class="a0m25c yp-liy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-align-middle" /></template>
