<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/h/hp8sgubia.css';
import '../../css/b/bwrud_gar.css';
import '../../css/n/ng_sv4rnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="hp8sgubia"/><path class="bwrud_gar"/><path class="ng_sv4rnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hi-five-logo" /></template>
