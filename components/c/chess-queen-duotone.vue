<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/ms8h6zb9e.css';
import '../../css/q/qhfur2bdl.css';
import '../../css/b/bw3ufyb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ms8h6zb9e"/><path class="qhfur2bdl"/><path class="bw3ufyb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chess-queen-duotone" /></template>
