<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ye5_bog.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5AuuMeAo"><path class="o0ye5_bog"/></mask></defs><path mask="url(#SVG5AuuMeAo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:down-two" /></template>
