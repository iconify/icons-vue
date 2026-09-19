<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/viij6dbqe.css';
import '../../css/q/qemtg7_xl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaNPXUb5M"><g class="v3_i3wktz"><path class="viij6dbqe"/><path class="qemtg7_xl"/></g></mask></defs><path mask="url(#SVGaNPXUb5M)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bring-forward" /></template>
