<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nfpxpmyht.css';
import '../../css/q/ql9sd2bvf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1aXMSbnJ"><g class="v3_i3wktz"><path class="nfpxpmyht"/><path class="ql9sd2bvf"/></g></mask></defs><path mask="url(#SVG1aXMSbnJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:alarm-clock" /></template>
