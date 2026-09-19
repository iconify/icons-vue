<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/l/lmm5f77sk.css';
import '../../css/r/rgqhnbciz.css';
import '../../css/o/o4fuzn82d.css';
import '../../css/y/ybt2h0but.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhNMHdODu"><g class="gopnm44um"><path class="lmm5f77sk"/><path class="rgqhnbciz"/><path class="o4fuzn82d"/><path class="ybt2h0but"/></g></mask></defs><path mask="url(#SVGhNMHdODu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:excel" /></template>
