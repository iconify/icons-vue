<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o2gaz3blc.css';
import '../../css/g/g163uejcd.css';
import '../../css/r/r2e8nk8aq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz6N0LYik"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="o2gaz3blc"/><path class="g163uejcd"/><path class="r2e8nk8aq"/></g></mask></defs><path mask="url(#SVGz6N0LYik)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:germs" /></template>
