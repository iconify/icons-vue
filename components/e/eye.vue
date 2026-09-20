<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sc0c9hqgy.css';
import '../../css/t/tkn-bnbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sc0c9hqgy"/><path class="tkn-bnbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:eye" /></template>
