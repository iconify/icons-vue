<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lr51ahzia.css';
import '../../css/a/acqctfqtk.css';
import '../../css/a/a6gtcl42r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lr51ahzia"/><path clip-rule="evenodd" class="acqctfqtk"/><path class="a6gtcl42r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cassette-filled" /></template>
