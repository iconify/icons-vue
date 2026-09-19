<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hoq0lh4ti.css';
import '../../css/t/t25bmmb3e.css';
import '../../css/h/hejmxi8qr.css';
import '../../css/o/ohhhkgs9i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4atfVdda"><g class="v3_i3wktz"><path class="hoq0lh4ti"/><path class="t25bmmb3e"/><path class="hejmxi8qr"/><ellipse class="ohhhkgs9i"/></g></mask></defs><path mask="url(#SVG4atfVdda)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:ipo" /></template>
