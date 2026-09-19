<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pu3c7wbmz.css';
import '../../css/y/y8nllnb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="checkbox-checked-outlined"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="pu3c7wbmz"/><path class="y8nllnb_t"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:checkbox-checked-outlined" /></template>
