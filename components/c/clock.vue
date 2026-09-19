<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm_fzdbbs.css';
import '../../css/g/gzm0_xb-h.css';
import '../../css/e/ev2wzjerc.css';
import '../../css/q/qa0kplb8m.css';
import '../../css/b/bwdpl5zyw.css';
import '../../css/u/u3apw6wjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xm_fzdbbs"/><circle class="gzm0_xb-h"/><path class="ev2wzjerc"/><path class="qa0kplb8m"/><circle class="bwdpl5zyw"/><circle class="u3apw6wjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:clock" /></template>
