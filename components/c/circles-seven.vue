<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktrttabkl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGN8D5Ad5C"><path clip-rule="evenodd" class="ktrttabkl"/></mask></defs><path mask="url(#SVGN8D5Ad5C)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:circles-seven" /></template>
