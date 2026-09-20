<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r4_tdob4v.css';
import '../../css/b/btuwcu4kf.css';
import '../../css/l/lo1_5i7tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r4_tdob4v"/><path class="btuwcu4kf"/><path class="lo1_5i7tr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase3-duotone" /></template>
