<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mg6s-wbot.css';
import '../../css/z/zoo1_zb4o.css';
import '../../css/u/uettqb7vg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUGvgaddU"><g class="aql7dnt-u"><circle class="mg6s-wbot"/><path class="zoo1_zb4o"/><path class="uettqb7vg"/></g></mask></defs><path mask="url(#SVGUGvgaddU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:boy" /></template>
