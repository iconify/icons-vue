<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xomud01jy.css';
import '../../css/h/hp1ekwx9t.css';
import '../../css/f/f5mmvebtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="xomud01jy"/><path clip-rule="evenodd" class="hp1ekwx9t"/><path clip-rule="evenodd" class="f5mmvebtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:arduino" /></template>
