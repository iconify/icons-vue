<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/l/l43khq9vu.css';
import '../../css/b/bkqngzb1q.css';
import '../../css/z/zcdnfrb8t.css';
import '../../css/j/jgtis7b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="l43khq9vu"/><path class="bkqngzb1q wm-shine"/><path class="zcdnfrb8t"/><path class="jgtis7b9v wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:git-pull-request" /></template>
