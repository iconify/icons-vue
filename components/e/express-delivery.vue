<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/b3d8bdqux.css';
import '../../css/g/gfmcy23iy.css';
import '../../css/b/bj4z4zz1e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaKYXIFAT"><g class="v3_i3wktz"><path class="b3d8bdqux"/><path class="gfmcy23iy"/><path class="bj4z4zz1e"/></g></mask></defs><path mask="url(#SVGaKYXIFAT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:express-delivery" /></template>
