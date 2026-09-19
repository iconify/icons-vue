<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sco-lqgta.css';
import '../../css/n/ny92e0b3s.css';
import '../../css/d/d3lktyezi.css';
import '../../css/s/s8xi34pba.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQMriXbAv"><g class="aql7dnt-u"><path class="sco-lqgta"/><path class="ny92e0b3s"/><path class="d3lktyezi"/><path class="s8xi34pba"/></g></mask></defs><path mask="url(#SVGQMriXbAv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hospital-two" /></template>
