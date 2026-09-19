<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yih83mira.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxYujDeIh"><path class="yih83mira"/></mask></defs><path mask="url(#SVGxYujDeIh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:left-two" /></template>
