<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zlp0m-w_h.css';
import '../../css/b/bos2ggy-f.css';
import '../../css/h/h8bzekbxe.css';
import '../../css/o/ow0i9rbvq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvW7cIE9T"><g class="ft5dv1b6b"><path class="zlp0m-w_h"/><path class="bos2ggy-f"/><path clip-rule="evenodd" class="h8bzekbxe"/><path class="ow0i9rbvq"/></g></mask></defs><path mask="url(#SVGvW7cIE9T)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bike" /></template>
