<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tj6aivbzl.css';
import '../../css/z/z5f4e7bex.css';
import '../../css/v/vuc8qmhxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><ellipse class="tj6aivbzl"/><path class="z5f4e7bex"/><path class="vuc8qmhxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:database" /></template>
