<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l_3txeeom.css';
import '../../css/n/nhyz14bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="matrix(0 -1 -1 0 18 20)" class="l_3txeeom"/><path class="nhyz14bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:load-circle-duotone" /></template>
