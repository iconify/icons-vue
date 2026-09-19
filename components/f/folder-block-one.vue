<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/v/vp420rb5o.css';
import '../../css/k/kuigothyl.css';
import '../../css/b/bbiysdm9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="vp420rb5o"/><circle class="kuigothyl"/><path class="bbiysdm9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-block-one" /></template>
