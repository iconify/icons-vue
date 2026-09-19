<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgepj_2fe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXyBFNeJE"><path class="jgepj_2fe"/></mask></defs><path mask="url(#SVGXyBFNeJE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cool" /></template>
