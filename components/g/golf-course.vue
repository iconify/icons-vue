<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hm6futw9s.css';
import '../../css/h/hexer05rq.css';
import '../../css/u/u6a29ib_h.css';
import '../../css/y/yhpinr7sk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzPFmmcVH"><g class="ft5dv1b6b"><ellipse class="hm6futw9s"/><circle class="hexer05rq"/><path class="u6a29ib_h"/><path class="yhpinr7sk"/></g></mask></defs><path mask="url(#SVGzPFmmcVH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:golf-course" /></template>
