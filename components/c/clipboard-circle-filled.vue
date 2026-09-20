<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/i/ivjvz2eii.css';
import '../../css/e/ey2r02nhy.css';
import '../../css/w/wmqr3wb9e.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG3eLDbwnR"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="ey2r02nhy"/><path class="wmqr3wb9e"/></g></mask></defs><circle mask="url(#SVG3eLDbwnR)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:clipboard-circle-filled" /></template>
