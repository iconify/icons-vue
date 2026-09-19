<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xvd3pkbjc.css';
import '../../css/t/tek6cfbxc.css';
import '../../css/t/t32bs5kub.css';
import '../../css/c/c-u1scctq.css';
import '../../css/u/uzcaltb9w.css';
import '../../css/n/nd713rb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path clip-rule="evenodd" class="xvd3pkbjc"/><path class="tek6cfbxc"/><path class="t32bs5kub"/><path class="c-u1scctq"/><path class="uzcaltb9w"/><path class="nd713rb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:clear" /></template>
