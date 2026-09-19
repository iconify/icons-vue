<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sla-trbaw.css';
import '../../css/y/y56puac6x.css';
import '../../css/d/dmkk9tbyk.css';
import '../../css/a/auejspbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sla-trbaw"/><path class="y56puac6x"/><path class="dmkk9tbyk"/><path class="auejspbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:camera-outline" /></template>
