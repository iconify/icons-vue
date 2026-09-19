<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xmsctmb7o.css';
import '../../css/z/z4pw7mbwo.css';
import '../../css/j/j42_cub7o.css';
import '../../css/u/uji50pb4n.css';
import '../../css/t/t5w_olbtz.css';
import '../../css/b/bisfjsret.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xmsctmb7o"/><path class="z4pw7mbwo"/><path class="j42_cub7o"/><path class="uji50pb4n"/><path class="t5w_olbtz"/><path class="bisfjsret"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:album-outline" /></template>
