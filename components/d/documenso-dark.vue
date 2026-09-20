<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/m/mntwwlban.css';
import '../../css/r/rb7nm4b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g clip-rule="evenodd" class="nx5d-bc1s"><path class="mntwwlban"/><path class="rb7nm4b1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:documenso-dark" /></template>
