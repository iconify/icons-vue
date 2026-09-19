<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/z/zsjkbubwq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmpuGweUz"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="zsjkbubwq"/></g></mask></defs><path mask="url(#SVGmpuGweUz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:adobe-lightroom" /></template>
