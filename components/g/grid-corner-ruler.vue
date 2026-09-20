<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p18lntbms.css';
import '../../css/z/zqgxlpbyx.css';
import '../../css/i/i73p8iv3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p18lntbms"/><path class="zqgxlpbyx"/><path class="i73p8iv3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:grid-corner-ruler" /></template>
