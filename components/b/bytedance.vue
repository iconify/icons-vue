<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrntwhbvb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRteyjMar"><path class="vrntwhbvb"/></mask></defs><path mask="url(#SVGRteyjMar)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bytedance" /></template>
