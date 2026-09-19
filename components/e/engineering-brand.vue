<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gwye36byq.css';
import '../../css/b/blg8u174q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKLmrrc1o"><g class="v3_i3wktz"><rect class="gwye36byq"/><path class="blg8u174q"/></g></mask></defs><path mask="url(#SVGKLmrrc1o)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:engineering-brand" /></template>
