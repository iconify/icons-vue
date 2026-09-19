<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e_shtx8ok.css';
import '../../css/k/kxk1ljbls.css';
import '../../css/e/eko1wqb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="e_shtx8ok"/><path class="kxk1ljbls"/><path class="eko1wqb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mail-inbox" /></template>
