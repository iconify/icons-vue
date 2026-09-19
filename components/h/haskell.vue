<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1i5j5zjy.css';
import '../../css/t/tsra2_hxh.css';
import '../../css/n/n6dcl9bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h1i5j5zjy"/><path class="tsra2_hxh"/><path class="n6dcl9bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:haskell" /></template>
