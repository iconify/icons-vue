<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9-40bub.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q8zxzbcvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":145,"height":32};
const content = `<clipPath id="SVGTztPORtj"><path class="db9-40bub"/></clipPath><g clip-path="url(#SVGTztPORtj)" class="ft5dv1b6b"><path clip-rule="evenodd" class="q8zxzbcvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kamal" /></template>
