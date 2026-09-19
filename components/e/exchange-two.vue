<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bco27yqdx.css';
import '../../css/d/dwfg7kbwe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCgko6bsd"><g class="wwvp95byt"><path class="bco27yqdx"/><path class="dwfg7kbwe"/></g></mask></defs><path mask="url(#SVGCgko6bsd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:exchange-two" /></template>
