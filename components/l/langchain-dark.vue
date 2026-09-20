<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/u/uxyucchry.css';
import '../../css/d/d8xt5fekw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGZWgQRzIM)" class="n1mjunbsu"><path class="uxyucchry"/></g><defs><clipPath id="SVGZWgQRzIM"><path class="d8xt5fekw"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:langchain-dark" /></template>
