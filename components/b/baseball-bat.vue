<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/z/zrcrh4bnb.css';
import '../../css/j/jxmh2ibtp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGltRESdbX"><g class="v1_swcb_o"><circle class="zrcrh4bnb"/><path class="jxmh2ibtp"/></g></mask></defs><path mask="url(#SVGltRESdbX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:baseball-bat" /></template>
