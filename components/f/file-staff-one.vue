<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/smvgv0b2x.css';
import '../../css/w/w8qln35qt.css';
import '../../css/i/im-kzebzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="smvgv0b2x"/><circle class="w8qln35qt"/><path class="im-kzebzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-staff-one" /></template>
