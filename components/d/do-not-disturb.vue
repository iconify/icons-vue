<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8550rb9o.css';
import '../../css/d/dvr3kccns.css';
import '../../css/z/z3s59cbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":24};
const content = `<path class="x8550rb9o"/><path class="dvr3kccns"/><path class="z3s59cbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:do-not-disturb" /></template>
