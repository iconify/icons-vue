<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ylbwe21du.css';
import '../../css/p/p_ypczfrf.css';
import '../../css/s/s3rrnwb-t.css';
import '../../css/o/omr3ux96y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWnl8ue9k"><g class="ft5dv1b6b"><ellipse class="ylbwe21du"/><ellipse class="p_ypczfrf"/><path class="s3rrnwb-t"/><ellipse class="omr3ux96y"/></g></mask></defs><path mask="url(#SVGWnl8ue9k)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:face-powder" /></template>
