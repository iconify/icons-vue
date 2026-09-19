<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/u9j2jq8qm.css';
import '../../css/h/hfdlftbfd.css';
import '../../css/k/ktvyjx33i.css';
import '../../css/e/efzxyzb1i.css';
import '../../css/v/vn34bdcic.css';
import '../../css/w/wd0-cz21h.css';
import '../../css/z/z14fekb7u.css';
import '../../css/k/ktfjgbc-g.css';
import '../../css/j/jknmelb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":200};
const content = `<g class="bi12bsetm"><path class="u9j2jq8qm"/><path class="hfdlftbfd"/><path class="ktvyjx33i"/><path class="efzxyzb1i"/><path class="vn34bdcic"/><path class="wd0-cz21h"/><path class="z14fekb7u"/><path class="ktfjgbc-g"/><path class="jknmelb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ao" /></template>
