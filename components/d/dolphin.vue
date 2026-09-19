<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg2dmo1tu.css';
import '../../css/h/hb6p0db8j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlCaPwdaD"><g class="ft5dv1b6b"><path class="rg2dmo1tu"/><circle class="hb6p0db8j"/></g></mask></defs><path mask="url(#SVGlCaPwdaD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:dolphin" /></template>
