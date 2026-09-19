<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/ecqskqbjc.css';
import '../../css/v/vhhxkzb1a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMXrrCcnc"><g class="v3_i3wktz"><path class="ecqskqbjc"/><path class="vhhxkzb1a"/></g></mask></defs><path mask="url(#SVGMXrrCcnc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:flask" /></template>
