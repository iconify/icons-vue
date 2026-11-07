<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9h01f9wo.css';
import '../../css/o/oiqop8ebf.css';
import '../../css/b/bvct38blc.css';
import '../../css/a/abgizhdkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9h01f9wo"/><path class="oiqop8ebf"/><path class="bvct38blc"/><path class="abgizhdkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-close-bold" /></template>
