<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/a9oobvrrl.css';
import '../../css/q/q9twg8bgx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGo5ZyMvxE"><g class="aql7dnt-u"><path clip-rule="evenodd" class="a9oobvrrl"/><path class="q9twg8bgx"/></g></mask></defs><path mask="url(#SVGo5ZyMvxE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:building-four" /></template>
