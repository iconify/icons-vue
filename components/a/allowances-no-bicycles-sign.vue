<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/am1ovqb9r.css';
import '../../css/h/h0ffmhi_f.css';
import '../../css/e/e5p014b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="am1ovqb9r"/><path class="h0ffmhi_f"/><path class="e5p014b7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:allowances-no-bicycles-sign" /></template>
