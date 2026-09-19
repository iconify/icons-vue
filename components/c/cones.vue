<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/t/txhjy5bum.css';
import '../../css/j/j7b_4jb0s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDZvEddeV"><g class="ufeehvblu"><path class="txhjy5bum"/><path class="j7b_4jb0s"/></g></mask></defs><path mask="url(#SVGDZvEddeV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cones" /></template>
