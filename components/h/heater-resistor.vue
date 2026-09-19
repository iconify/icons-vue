<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/ag041nb8r.css';
import '../../css/q/q-jxeyn0g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGi6jqRcXl"><g class="v3_i3wktz"><rect transform="rotate(-45 9.858 29.657)" class="ag041nb8r"/><path class="q-jxeyn0g"/></g></mask></defs><path mask="url(#SVGi6jqRcXl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:heater-resistor" /></template>
