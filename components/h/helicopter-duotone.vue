<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o4avq6bbw.css';
import '../../css/r/rbfuzcbwl.css';
import '../../css/j/jf8b9ilbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o4avq6bbw"/><path class="rbfuzcbwl"/><path class="jf8b9ilbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:helicopter-duotone" /></template>
