<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/a/aljcmyiym.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoY0gucgE"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="aljcmyiym"/></g></mask></defs><path mask="url(#SVGoY0gucgE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:alignment-horizontal-top" /></template>
