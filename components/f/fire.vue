<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/parj51b-v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9H2JBOPY"><path class="parj51b-v"/></mask></defs><path mask="url(#SVG9H2JBOPY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:fire" /></template>
