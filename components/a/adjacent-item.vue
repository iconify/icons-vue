<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ex0re0kub.css';
import '../../css/f/f31473-bi.css';
import '../../css/n/n-s0fvqfw.css';
import '../../css/k/kjv48vx0m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVuIdSd6J"><g class="ft5dv1b6b"><path class="ex0re0kub"/><path class="f31473-bi"/><path class="n-s0fvqfw"/><path class="kjv48vx0m"/></g></mask></defs><path mask="url(#SVGVuIdSd6J)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:adjacent-item" /></template>
