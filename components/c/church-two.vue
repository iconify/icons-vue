<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/f/ft9w2fb4q.css';
import '../../css/h/hocjhx65h.css';
import '../../css/a/a3x0wi1cq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGp2QLQbYX"><g class="hv130ab-t"><path class="ft9w2fb4q"/><path class="hocjhx65h"/><path class="a3x0wi1cq"/></g></mask></defs><path mask="url(#SVGp2QLQbYX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:church-two" /></template>
