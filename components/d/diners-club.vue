<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skehb9b_e.css';
import '../../css/v/v9_061blr.css';
import '../../css/p/ptx8jiyoi.css';
import '../../css/r/r8y5pebry.css';
import '../../css/b/bq5-wbb3q.css';
import '../../css/e/e2k5-xbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="skehb9b_e"/><path class="v9_061blr"/><path class="ptx8jiyoi"/><path clip-rule="evenodd" class="r8y5pebry"/><path clip-rule="evenodd" class="bq5-wbb3q"/><path clip-rule="evenodd" class="e2k5-xbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:diners-club" /></template>
