<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ccn4zactj.css';
import '../../css/b/bhk8wfb4o.css';
import '../../css/c/cb49zqzuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ccn4zactj"/><path class="bhk8wfb4o"/><path class="cb49zqzuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:iv-bag-duotone" /></template>
