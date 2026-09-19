<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gdklhuebv.css';
import '../../css/o/ouwye0b8s.css';
import '../../css/f/f5w20rbat.css';
import '../../css/h/hrlhvxdnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gdklhuebv"/><path class="ouwye0b8s"/><path class="f5w20rbat"/><path class="hrlhvxdnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-bill-outline" /></template>
