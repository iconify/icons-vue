<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj_cxkkhb.css';
import '../../css/o/o6uly9l0b.css';
import '../../css/s/sn2vv6rhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hj_cxkkhb"/><path class="o6uly9l0b"/><path class="sn2vv6rhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fanqiexiaoshuo" /></template>
