<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/crvfg_zef.css';
import '../../css/a/a30gdttzf.css';
import '../../css/b/bo93y_ztc.css';
import '../../css/s/s26qisbtl.css';
import '../../css/s/scaplnjbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="crvfg_zef"/><path class="a30gdttzf"/><path clip-rule="evenodd" class="bo93y_ztc"/><path clip-rule="evenodd" class="s26qisbtl"/><path clip-rule="evenodd" class="scaplnjbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hand-wipe-paper" /></template>
