<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bfsv7cc4c.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/h/h111i6rqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bfsv7cc4c"/><path class="ml0cb1b5h"/><path class="h111i6rqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-broken" /></template>
