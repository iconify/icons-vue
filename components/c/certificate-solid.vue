<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/iijut148h.css';
import '../../css/v/vgjh9ibgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="iijut148h"/><path class="vgjh9ibgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:certificate-solid" /></template>
