<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb9ajhbky.css';
import '../../css/w/w_7rm3j9j.css';
import '../../css/f/f_t5h2bth.css';
import '../../css/i/i2ck-cb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb9ajhbky"/><path class="w_7rm3j9j"/><path class="f_t5h2bth"/><path class="i2ck-cb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:annotation-visibility" /></template>
