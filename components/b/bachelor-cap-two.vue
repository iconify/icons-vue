<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x4rmk8quk.css';
import '../../css/u/uybie1zay.css';
import '../../css/a/aufer1bkq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGin54IcQU"><g class="v3_i3wktz"><path class="x4rmk8quk"/><path class="uybie1zay"/><path class="aufer1bkq"/></g></mask></defs><path mask="url(#SVGin54IcQU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bachelor-cap-two" /></template>
