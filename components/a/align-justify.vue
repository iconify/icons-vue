<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/w/w20zkn.css';
import '../../css/j/jpz_dx.css';
import '../../css/a/a7xz6k.css';
import '../../css/s/so-from-8.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c w20zkn"/><path class="a0m25c jpz_dx"/><path class="a0m25c a7xz6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:align-justify" /></template>
