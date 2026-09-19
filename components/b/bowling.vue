<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek-wxnthc.css';
import '../../css/j/j-tdi7bib.css';
import '../../css/p/pre-thz9w.css';
import '../../css/y/y9cl-l_4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ek-wxnthc"/><circle class="j-tdi7bib"/><circle class="pre-thz9w"/><circle class="y9cl-l_4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bowling" /></template>
