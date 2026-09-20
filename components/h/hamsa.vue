<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elw13eb3k.css';
import '../../css/n/n2me6q61h.css';
import '../../css/l/lqe4j-bcx.css';
import '../../css/w/wa1g8vb3f.css';
import '../../css/r/rzmrbebwf.css';
import '../../css/o/o65o_hb_z.css';
import '../../css/f/fbsu__bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="elw13eb3k"/><path class="n2me6q61h"/><circle class="lqe4j-bcx"/><path class="wa1g8vb3f"/><path class="rzmrbebwf"/><circle class="o65o_hb_z"/><circle class="fbsu__bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hamsa" /></template>
