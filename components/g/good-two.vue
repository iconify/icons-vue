<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6mkcxi9w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9QFFpbBI"><path class="u6mkcxi9w"/></mask></defs><path mask="url(#SVG9QFFpbBI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:good-two" /></template>
