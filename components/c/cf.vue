<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rehki8kvn.css';
import '../../css/d/d7xvmv0ip.css';
import '../../css/c/cfl7k-b9e.css';
import '../../css/i/ilqy7wboq.css';
import '../../css/e/eqytyfu7c.css';
import '../../css/e/eupkuwbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rehki8kvn"/><path class="d7xvmv0ip"/><path class="cfl7k-b9e"/><path class="ilqy7wboq"/><path class="eqytyfu7c"/><path class="eupkuwbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:cf" /></template>
