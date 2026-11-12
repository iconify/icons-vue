<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xblvs3bpj.css';
import '../../css/x/xj4e8-rbm.css';
import '../../css/z/z98gm69xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xblvs3bpj"/><path class="xj4e8-rbm"/><path class="z98gm69xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:leafwiki" /></template>
