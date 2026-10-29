<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/ltcazkbqu.css';
import '../../css/t/tp-yo7b2q.css';
import '../../css/a/aaymibb1x.css';
import '../../css/d/d6i3s2dnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ltcazkbqu wm-deco"/><path class="tp-yo7b2q wm-deco"/><path class="aaymibb1x wm-k"/><path class="d6i3s2dnz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-commit-blueprint" /></template>
