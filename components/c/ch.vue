<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5kc42b7b.css';
import '../../css/j/jwcli6b-b.css';
import '../../css/s/siol5wblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":301};
const content = `<g class="ft5dv1b6b"><path class="t5kc42b7b"/><path class="jwcli6b-b"/><path class="siol5wblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ch" /></template>
