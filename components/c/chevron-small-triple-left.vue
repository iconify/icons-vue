<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/e/ew1mpj.css';
import '../../css/m/m0_dsb.css';
import '../../css/j/ju1zuh.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ew1mpj"/><path class="a0m25c m0_dsb"/><path class="a0m25c ju1zuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-triple-left" /></template>
