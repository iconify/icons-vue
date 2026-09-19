<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/w/wscs-dz5a.css';
import '../../css/x/x0pbd8bzp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7H5AvcQt"><g class="v3_i3wktz"><path class="wscs-dz5a"/><path class="x0pbd8bzp"/></g></mask></defs><path mask="url(#SVG7H5AvcQt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:coupon" /></template>
