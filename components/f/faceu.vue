<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fux8zqblx.css';
import '../../css/q/q1sc_2b4t.css';
import '../../css/w/w7g5_yhdp.css';
import '../../css/h/hk_6th-pz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYra3uiyH"><g class="ft5dv1b6b"><path class="fux8zqblx"/><path class="q1sc_2b4t"/><ellipse class="w7g5_yhdp"/><ellipse class="hk_6th-pz"/></g></mask></defs><path mask="url(#SVGYra3uiyH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:faceu" /></template>
