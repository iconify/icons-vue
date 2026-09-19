<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-1r0llge.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGx6kK0d0v"><path class="w-1r0llge"/></mask></defs><path mask="url(#SVGx6kK0d0v)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:horizontal-tidy-up" /></template>
