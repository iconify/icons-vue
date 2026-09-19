<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cm4astalv.css';
import '../../css/u/utwll5b5g.css';
import '../../css/l/lj7iiqb-j.css';
import '../../css/d/d-02mibho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm4astalv"/><path class="utwll5b5g"/><path class="lj7iiqb-j"/><path class="d-02mibho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:database-backup" /></template>
