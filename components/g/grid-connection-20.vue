<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lct1fn02i.css';
import '../../css/h/h_ct2hn4p.css';
import '../../css/j/jdhs7_bdy.css';
import '../../css/w/wwfzbmz9y.css';
import '../../css/j/jtx38t8rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lct1fn02i"/><path class="h_ct2hn4p"/><path class="jdhs7_bdy"/><path class="wwfzbmz9y"/><path class="jtx38t8rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-connection-20" /></template>
