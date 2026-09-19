<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yk7vkkbvp.css';
import '../../css/w/wsqwqiv3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="yk7vkkbvp"/><path class="wsqwqiv3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:critical-care2x-outline" /></template>
