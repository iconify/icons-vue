<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z2og0bbcd.css';
import '../../css/z/z_eskmbbe.css';
import '../../css/q/qcrfezbia.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeCtwbdKx"><g class="ft5dv1b6b"><path class="z2og0bbcd"/><path class="z_eskmbbe"/><path class="qcrfezbia"/></g></mask></defs><path mask="url(#SVGeCtwbdKx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mail-download" /></template>
