<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/txwygjb8d.css';
import '../../css/w/wyahbkbgb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXSFC601V"><g class="ufeehvblu"><path class="txwygjb8d"/><path class="wyahbkbgb"/></g></mask></defs><path mask="url(#SVGXSFC601V)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:config" /></template>
