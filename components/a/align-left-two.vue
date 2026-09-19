<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4qqmmb7p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9ZpiTHEA"><path class="r4qqmmb7p"/></mask></defs><path mask="url(#SVG9ZpiTHEA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-left-two" /></template>
