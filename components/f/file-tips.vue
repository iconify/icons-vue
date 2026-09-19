<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z4n05zl7r.css';
import '../../css/g/gbvnb5bkp.css';
import '../../css/e/eeud-mw1p.css';
import '../../css/n/nbfw7rpxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="z4n05zl7r"/><path class="gbvnb5bkp"/><path class="eeud-mw1p"/><path clip-rule="evenodd" class="nbfw7rpxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:file-tips" /></template>
