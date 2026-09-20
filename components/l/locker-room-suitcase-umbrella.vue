<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dm0kexnkt.css';
import '../../css/g/gwjpso23e.css';
import '../../css/l/lc1x4oxgh.css';
import '../../css/x/x23oeih7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dm0kexnkt"/><path class="gwjpso23e"/><path class="lc1x4oxgh"/><path class="x23oeih7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:locker-room-suitcase-umbrella" /></template>
