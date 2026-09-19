<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b73xzkmwr.css';
import '../../css/t/ta5echf4d.css';
import '../../css/l/lq66sib7a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9hkELdcV"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="b73xzkmwr"/><path class="ta5echf4d"/><path class="lq66sib7a"/></g></mask></defs><path mask="url(#SVG9hkELdcV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-histogram-two" /></template>
