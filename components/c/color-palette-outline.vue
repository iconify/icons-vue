<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6dw9bpm.css';
import '../../css/a/a9drticeq.css';
import '../../css/k/klvat-kpw.css';
import '../../css/a/ar4i5wb4o.css';
import '../../css/z/zozx40bsi.css';
import '../../css/c/cwvxs5onk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hw6dw9bpm"/><circle class="a9drticeq"/><circle class="klvat-kpw"/><circle class="ar4i5wb4o"/><circle class="zozx40bsi"/><circle class="cwvxs5onk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-palette-outline" /></template>
