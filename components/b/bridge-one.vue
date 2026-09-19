<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy4t3zb5c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMPVN8ciM"><path class="iy4t3zb5c"/></mask></defs><path mask="url(#SVGMPVN8ciM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bridge-one" /></template>
