<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en0_brpcp.css';
import '../../css/s/sx0whwb_m.css';
import '../../css/j/jnnkanbzp.css';
import '../../css/i/i_umbcdgk.css';
import '../../css/s/slwx9s0lo.css';
import '../../css/n/nfeshnb-t.css';
import '../../css/f/fyydeobbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="en0_brpcp"/><path class="sx0whwb_m"/><path class="jnnkanbzp"/><path class="i_umbcdgk"/><path class="slwx9s0lo"/><path class="nfeshnb-t"/><path class="fyydeobbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:brazil" /></template>
