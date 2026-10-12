<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cal32lbgc.css';
import '../../css/r/rgggbcbui.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/j/j-6jq5b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cal32lbgc"/><path class="rgggbcbui"/><path class="g4vvtk_cw"/><path clip-rule="evenodd" class="j-6jq5b4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-user-round-duotone" /></template>
