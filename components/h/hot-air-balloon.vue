<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cef01bcjg.css';
import '../../css/a/afb9b6fbe.css';
import '../../css/r/r7pgu-b1y.css';
import '../../css/m/mfz_dvbkz.css';
import '../../css/p/p3nxasb2v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb7lRybDH"><g class="ft5dv1b6b"><path class="cef01bcjg"/><path class="afb9b6fbe"/><path class="r7pgu-b1y"/><path class="mfz_dvbkz"/><path class="p3nxasb2v"/></g></mask></defs><path mask="url(#SVGb7lRybDH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hot-air-balloon" /></template>
