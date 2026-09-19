<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f76solb2x.css';
import '../../css/u/usxvrsb_d.css';
import '../../css/u/umro_ab_l.css';
import '../../css/s/s1he6l30z.css';
import '../../css/h/hlpebobcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f76solb2x"/><path class="usxvrsb_d"/><circle class="umro_ab_l"/><path class="s1he6l30z"/><circle class="hlpebobcu"/><circle class="f76solb2x"/><circle class="hlpebobcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:conference-call" /></template>
