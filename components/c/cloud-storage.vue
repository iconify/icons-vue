<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-6grdhmq.css';
import '../../css/i/irl6mqbpf.css';
import '../../css/p/pgml1ac6f.css';
import '../../css/t/t5mh8hb-o.css';
import '../../css/p/pvctjpbam.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOZuD4cod"><g class="ft5dv1b6b"><path class="h-6grdhmq"/><path class="irl6mqbpf"/><path class="pgml1ac6f"/><path class="t5mh8hb-o"/><path class="pvctjpbam"/></g></mask></defs><path mask="url(#SVGOZuD4cod)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cloud-storage" /></template>
