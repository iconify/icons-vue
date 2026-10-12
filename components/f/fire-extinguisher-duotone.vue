<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/phqcj38vj.css';
import '../../css/r/r1rsxnb4u.css';
import '../../css/u/u5ok6zbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="phqcj38vj"/><path class="r1rsxnb4u"/><path class="u5ok6zbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fire-extinguisher-duotone" /></template>
