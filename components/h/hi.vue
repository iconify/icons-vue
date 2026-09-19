<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b74uycbvr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0J8iwcBH"><path class="b74uycbvr"/></mask></defs><path mask="url(#SVG0J8iwcBH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hi" /></template>
