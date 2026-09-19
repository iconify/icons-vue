<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ude9i169c.css';
import '../../css/n/n1hfnlbgv.css';
import '../../css/a/azrmtruiz.css';
import '../../css/o/ots7eo6hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ude9i169c"/><path class="n1hfnlbgv"/><g><path class="azrmtruiz"/><path class="ots7eo6hs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-toggle-outline" /></template>
