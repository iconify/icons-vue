<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ze_xbnd.css';
import '../../css/o/o-ow-2npg.css';
import '../../css/h/hw5whrlil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7ze_xbnd"/><path class="o-ow-2npg"/><path class="hw5whrlil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cu3" /></template>
