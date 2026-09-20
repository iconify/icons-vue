<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra8x7z.css';
import '../../css/a/a0m25c.css';
import '../../css/a/am_aaq.css';
import '../../css/c/cn_flp.css';
import '../../css/j/jkbtbq.css';
import '../../css/h/he9snp.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra8x7z"/><path class="a0m25c am_aaq"/><path class="a0m25c cn_flp"/><path class="a0m25c jkbtbq"/><path class="a0m25c he9snp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-down-twotone" /></template>
