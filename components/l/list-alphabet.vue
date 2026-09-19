<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tx0vkcbsy.css';
import '../../css/i/iarpp2o_e.css';
import '../../css/h/hk6ft-98v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYl1ZTd2R"><g class="ft5dv1b6b"><path class="tx0vkcbsy"/><path class="iarpp2o_e"/><path class="hk6ft-98v"/></g></mask></defs><path mask="url(#SVGYl1ZTd2R)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:list-alphabet" /></template>
