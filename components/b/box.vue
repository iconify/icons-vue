<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kf9iljxev.css';
import '../../css/i/iog5bvc2b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDiIGbbnD"><g class="v3_i3wktz"><rect class="kf9iljxev"/><path class="iog5bvc2b"/></g></mask></defs><path mask="url(#SVGDiIGbbnD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:box" /></template>
