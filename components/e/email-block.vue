<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gzks8bcyr.css';
import '../../css/w/wso75kn4e.css';
import '../../css/b/bbiysdm9e.css';
import '../../css/s/sarx32axf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="gzks8bcyr"/><circle class="wso75kn4e"/><path class="bbiysdm9e"/><path class="sarx32axf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:email-block" /></template>
