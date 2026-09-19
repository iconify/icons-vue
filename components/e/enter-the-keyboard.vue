<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rgna-dbok.css';
import '../../css/w/w-46dcbay.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSgjLNcpB"><g class="v3_i3wktz"><path class="rgna-dbok"/><path class="w-46dcbay"/></g></mask></defs><path mask="url(#SVGSgjLNcpB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:enter-the-keyboard" /></template>
