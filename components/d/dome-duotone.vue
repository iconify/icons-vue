<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jte9y4bzl.css';
import '../../css/h/h78kjxbop.css';
import '../../css/d/ds0tozb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jte9y4bzl"/><path class="h78kjxbop"/><path class="ds0tozb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dome-duotone" /></template>
