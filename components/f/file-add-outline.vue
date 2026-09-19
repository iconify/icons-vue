<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m4r0j2uqu.css';
import '../../css/o/ojbsnh9jw.css';
import '../../css/p/pyscf72-e.css';
import '../../css/s/sfzlwaceu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="m4r0j2uqu"/><path clip-rule="evenodd" class="ojbsnh9jw"/><path class="pyscf72-e"/><path clip-rule="evenodd" class="sfzlwaceu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:file-add-outline" /></template>
