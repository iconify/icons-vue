<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jain414ui.css';
import '../../css/r/r_0d81uyp.css';
import '../../css/e/eel2labxa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJs3Xyesl"><g class="ft5dv1b6b"><rect transform="rotate(-90 14 44)" class="jain414ui"/><path class="r_0d81uyp"/><path class="eel2labxa"/></g></mask></defs><path mask="url(#SVGJs3Xyesl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-storage" /></template>
