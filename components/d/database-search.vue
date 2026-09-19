<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h3clwtb7p.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/d/dt8z6xb6l.css';
import '../../css/i/iq7gmc7md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h3clwtb7p"/><ellipse class="h_l78yaxm"/><path class="dt8z6xb6l"/><path class="iq7gmc7md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database-search" /></template>
