<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fdlsegbxw.css';
import '../../css/q/qxakhabnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path clip-rule="evenodd" class="fdlsegbxw"/><path class="qxakhabnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:data-arrival" /></template>
