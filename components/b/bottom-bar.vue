<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/d/dwxh3eb8p.css';
import '../../css/j/jf883isdf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCn6z1b0J"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="dwxh3eb8p"/><path class="jf883isdf"/></g></mask></defs><path mask="url(#SVGCn6z1b0J)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bottom-bar" /></template>
