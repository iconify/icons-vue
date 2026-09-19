<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wfwd8y9av.css';
import '../../css/r/rhy2hmbom.css';
import '../../css/g/gxnq7z-rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wfwd8y9av"/><path class="rhy2hmbom"/><path class="gxnq7z-rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:audit-01" /></template>
