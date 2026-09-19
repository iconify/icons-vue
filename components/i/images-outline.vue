<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m04wr6bxv.css';
import '../../css/h/h3e1u3zis.css';
import '../../css/i/i3c4jibtn.css';
import '../../css/x/xcv5olncc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m04wr6bxv"/><path class="h3e1u3zis"/><path class="i3c4jibtn"/><path class="xcv5olncc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:images-outline" /></template>
