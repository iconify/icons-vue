<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vw3t96bes.css';
import '../../css/z/zbz1lfb5t.css';
import '../../css/c/cnnjisezc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vw3t96bes"/><path class="zbz1lfb5t"/><path class="cnnjisezc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-cog-outline" /></template>
