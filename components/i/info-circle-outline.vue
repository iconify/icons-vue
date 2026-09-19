<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p83o8yqdi.css';
import '../../css/a/ayf976bbf.css';
import '../../css/d/d6l22yz_k.css';
import '../../css/d/ddq-3fb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p83o8yqdi"/><path clip-rule="evenodd" class="ayf976bbf"/><path class="d6l22yz_k"/><path clip-rule="evenodd" class="ddq-3fb3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:info-circle-outline" /></template>
