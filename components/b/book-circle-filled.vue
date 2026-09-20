<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/f/fhv7sem-x.css';
import '../../css/m/mro15pfsn.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGNu6sGdPq"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="fhv7sem-x"/><path class="mro15pfsn"/></g></mask></defs><circle mask="url(#SVGNu6sGdPq)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:book-circle-filled" /></template>
