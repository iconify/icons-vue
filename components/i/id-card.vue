<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pfvzz0gys.css';
import '../../css/z/ze54d44ll.css';
import '../../css/k/kxs16xb2x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGXg2icVX"><g class="v3_i3wktz"><path class="pfvzz0gys"/><path class="ze54d44ll"/><path class="kxs16xb2x"/></g></mask></defs><path mask="url(#SVGGXg2icVX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:id-card" /></template>
