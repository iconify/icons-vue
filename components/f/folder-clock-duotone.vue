<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_vd8w5qu.css';
import '../../css/t/t2kj8u-pi.css';
import '../../css/b/b2hl1gbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c_vd8w5qu"/><path class="t2kj8u-pi"/><path class="b2hl1gbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-clock-duotone" /></template>
