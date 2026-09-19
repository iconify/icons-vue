<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/d0_0fyo4s.css';
import '../../css/q/qqo604awj.css';
import '../../css/t/tr8estbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="d0_0fyo4s"/><path class="qqo604awj"/><path class="tr8estbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:eyebrow" /></template>
