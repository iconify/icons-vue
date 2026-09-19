<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up0-o6tjm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzJgSle4O"><path class="up0-o6tjm"/></mask></defs><path mask="url(#SVGzJgSle4O)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-three" /></template>
