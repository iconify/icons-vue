<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yygam6b7j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnnJ8QrkK"><path class="yygam6b7j"/></mask></defs><path mask="url(#SVGnnJ8QrkK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:airplane" /></template>
