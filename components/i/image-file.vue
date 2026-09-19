<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goohnvfrd.css';
import '../../css/z/z8ck8jbnx.css';
import '../../css/l/llok4vb-m.css';
import '../../css/b/bm19tu52u.css';
import '../../css/j/jkay9v9tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goohnvfrd"/><path class="z8ck8jbnx"/><path class="llok4vb-m"/><path class="bm19tu52u"/><circle class="jkay9v9tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:image-file" /></template>
