<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hsroorh1q.css';
import '../../css/p/pz8dnbcvz.css';
import '../../css/d/d9ssa1btu.css';
import '../../css/e/euj49csjz.css';
import '../../css/a/a39e54k6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hsroorh1q wm-k"/><path class="pz8dnbcvz wm-a"/><path class="d9ssa1btu wm-shadow"/><path class="euj49csjz wm-k"/><path class="a39e54k6y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-engrave" /></template>
