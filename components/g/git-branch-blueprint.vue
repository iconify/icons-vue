<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/t4j37yb9a.css';
import '../../css/e/e1yc9ublt.css';
import '../../css/t/t218te2ox.css';
import '../../css/s/s2k53ac7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="t4j37yb9a wm-deco"/><path class="e1yc9ublt wm-deco"/><path class="t218te2ox wm-deco"/><path class="s2k53ac7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-blueprint" /></template>
