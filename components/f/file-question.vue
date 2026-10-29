<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/mjrcyhbre.css';
import '../../css/n/nk83n3bbi.css';
import '../../css/e/esa1d30xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="mjrcyhbre"/><path class="nk83n3bbi"/><path class="esa1d30xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:file-question" /></template>
