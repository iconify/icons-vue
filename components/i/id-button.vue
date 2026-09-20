<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brzn_0bpr.css';
import '../../css/p/puls3mbfe.css';
import '../../css/i/i13-gsb6n.css';
import '../../css/b/biji_vb8a.css';
import '../../css/c/c0czcirtf.css';
import '../../css/f/fyixbgitn.css';
import '../../css/i/inkh0sb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g transform="translate(0 -.014)" class="brzn_0bpr"><path clip-rule="evenodd" class="puls3mbfe"/><rect class="i13-gsb6n"/></g><g transform="translate(0 -.014)" class="biji_vb8a"><rect class="c0czcirtf"/><path clip-rule="evenodd" class="fyixbgitn"/><rect class="inkh0sb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:id-button" /></template>
