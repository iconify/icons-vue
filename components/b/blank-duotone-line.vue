<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9wrkjbdx.css';
import '../../css/b/bepdiosbn.css';
import '../../css/l/lrtfp_zks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f9wrkjbdx"/><path class="bepdiosbn"/><path class="lrtfp_zks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:blank-duotone-line" /></template>
