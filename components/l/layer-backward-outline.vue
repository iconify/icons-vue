<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/ju2v4eblp.css';
import '../../css/e/efrkp9byv.css';
import '../../css/s/s8ogcvbvw.css';
import '../../css/v/vbjxz-bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ju2v4eblp"/><path class="efrkp9byv"/><path class="s8ogcvbvw"/><path class="vbjxz-bhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-backward-outline" /></template>
