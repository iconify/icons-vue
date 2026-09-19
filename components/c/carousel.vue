<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/ppec674qb.css';
import '../../css/v/v968wactg.css';
import '../../css/e/e146jsbwe.css';
import '../../css/j/jfq0frq6e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8qUaQbUD"><g class="ufeehvblu"><path class="ppec674qb"/><path class="v968wactg"/><path class="e146jsbwe"/><path class="jfq0frq6e"/></g></mask></defs><path mask="url(#SVG8qUaQbUD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:carousel" /></template>
