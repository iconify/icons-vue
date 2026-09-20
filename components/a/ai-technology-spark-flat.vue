<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ux3ex7bqw.css';
import '../../css/c/cvkqkhbli.css';
import '../../css/u/uggzizsip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ux3ex7bqw"/><path class="cvkqkhbli"/><path class="uggzizsip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:ai-technology-spark-flat" /></template>
