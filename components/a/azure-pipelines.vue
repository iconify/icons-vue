<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9cn4oz7w.css';
import '../../css/f/fjvn43bcd.css';
import '../../css/z/z9wzhbchn.css';
import '../../css/c/c0yojvukz.css';
import '../../css/f/fq48kswtk.css';
import '../../css/l/ljqy3wb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h9cn4oz7w"/><path class="fjvn43bcd"/><path class="z9wzhbchn"/><path class="c0yojvukz"/><path class="fq48kswtk"/><path class="ljqy3wb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:azure-pipelines" /></template>
