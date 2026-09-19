<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/b5k2o3wfc.css';
import '../../css/a/amx419yok.css';
import '../../css/a/asllu_tlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="b5k2o3wfc"/><path class="amx419yok"/><path class="asllu_tlg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:boxing-glove" /></template>
