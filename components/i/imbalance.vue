<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/d08qanr9p.css';
import '../../css/g/gl1hokdww.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaFxh4cRS"><g class="aql7dnt-u"><path class="d08qanr9p"/><path clip-rule="evenodd" class="gl1hokdww"/></g></mask></defs><path mask="url(#SVGaFxh4cRS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:imbalance" /></template>
