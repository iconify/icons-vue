<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/z67tnutlr.css';
import '../../css/v/v1s64tbtd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNs1c1b9f"><g class="v3_i3wktz"><path class="z67tnutlr"/><path class="v1s64tbtd"/></g></mask></defs><path mask="url(#SVGNs1c1b9f)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-vertically" /></template>
