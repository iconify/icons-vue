<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ze_xbnd.css';
import '../../css/n/n1zl3pa7m.css';
import '../../css/c/c84vldf2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7ze_xbnd"/><path class="n1zl3pa7m"/><path class="c84vldf2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ccx" /></template>
