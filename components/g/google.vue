<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hp7rzjb5c.css';
import '../../css/q/qk2qv3bmt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNcVFUBwS"><g class="ft5dv1b6b"><path class="hp7rzjb5c"/><path class="qk2qv3bmt"/></g></mask></defs><path mask="url(#SVGNcVFUBwS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:google" /></template>
