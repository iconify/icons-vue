<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ak_jjqnlm.css';
import '../../css/q/q6trnobms.css';
import '../../css/q/qry3u0blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ak_jjqnlm"/><path class="q6trnobms"/><path class="qry3u0blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:ice-cream-2-flat" /></template>
