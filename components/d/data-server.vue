<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/v/v0bbswb4j.css';
import '../../css/q/qlkj-ye-j.css';
import '../../css/g/ga6yqxbkp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwCY6XcVw"><g class="hv130ab-t"><path class="v0bbswb4j"/><path class="qlkj-ye-j"/><path class="ga6yqxbkp"/></g></mask></defs><path mask="url(#SVGwCY6XcVw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:data-server" /></template>
