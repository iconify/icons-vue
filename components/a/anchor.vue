<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/eptqnp95c.css';
import '../../css/j/j9qe56bhi.css';
import '../../css/m/m3ykmcy1q.css';
import '../../css/y/yjl1c1boa.css';
import '../../css/j/j73mfxbcw.css';
import '../../css/a/a9bp5w-wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="eptqnp95c"/><rect class="j9qe56bhi"/><rect class="m3ykmcy1q"/><rect class="yjl1c1boa"/><rect class="j73mfxbcw"/><path class="a9bp5w-wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:anchor" /></template>
