<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxxz6v6tu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtMBvKcON"><path class="hxxz6v6tu"/></mask></defs><path mask="url(#SVGtMBvKcON)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:like" /></template>
