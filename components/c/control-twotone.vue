<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8-4tb2b.css';
import '../../css/n/nw-f-lb0x.css';
import '../../css/t/t_p41ydtf.css';
import '../../css/a/advo7kb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="nw-f-lb0x"/><path class="t_p41ydtf"/><path class="advo7kb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:control-twotone" /></template>
