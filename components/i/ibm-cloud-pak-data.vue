<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6_c39_yy.css';
import '../../css/h/h6mek4bbm.css';
import '../../css/x/x2dd2ra1b.css';
import '../../css/z/z98ug6bzd.css';
import '../../css/d/dtq21bbhs.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="a6_c39_yy"/><circle class="h6mek4bbm"/><circle class="x2dd2ra1b"/><circle class="z98ug6bzd"/><path class="dtq21bbhs"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-data" /></template>
