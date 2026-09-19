<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/m3rbq0wjz.css';
import '../../css/f/freg9xhpy.css';
import '../../css/n/nzzcombqn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvDzqBcpF"><g class="aql7dnt-u"><path class="m3rbq0wjz"/><path class="freg9xhpy"/><path class="nzzcombqn"/></g></mask></defs><path mask="url(#SVGvDzqBcpF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-quality-one" /></template>
