<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivh1z7bdr.css';
import '../../css/b/b1k78hpfz.css';
import '../../css/w/wx04sccmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGpKYQeQOh" x1="60.97" x2="60.97" y1="-54.104" y2="167.839" gradientUnits="userSpaceOnUse"><stop offset="0" class="ivh1z7bdr"/><stop offset="1" class="b1k78hpfz"/></linearGradient></defs><path fill="url(#SVGpKYQeQOh)" class="wx04sccmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:binijs" /></template>
