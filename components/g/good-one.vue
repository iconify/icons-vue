<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbmp_lblq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4gDFRdvF"><path class="fbmp_lblq"/></mask></defs><path mask="url(#SVG4gDFRdvF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:good-one" /></template>
