<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/llpmbrbgw.css';
import '../../css/g/g0ufjysom.css';
import '../../css/r/rkquw6meg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuJOGTtAE"><g class="aql7dnt-u"><path class="llpmbrbgw"/><path class="g0ufjysom"/><path class="rkquw6meg"/></g></mask></defs><path mask="url(#SVGuJOGTtAE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:carousel-video" /></template>
