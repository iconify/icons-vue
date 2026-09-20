<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whfl3kb-r.css';
import '../../css/l/laz58e6cn.css';
import '../../css/j/jmtoiebca.css';
import '../../css/s/so4w25-jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":499.3,"height":72};
const content = `<path clip-rule="evenodd" class="whfl3kb-r"/><path class="laz58e6cn"/><path clip-rule="evenodd" class="jmtoiebca"/><path clip-rule="evenodd" class="so4w25-jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:austrian-airlines" /></template>
