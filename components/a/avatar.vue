<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ljm0bnq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIzsXqb4I"><path class="u_ljm0bnq"/></mask></defs><path mask="url(#SVGIzsXqb4I)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:avatar" /></template>
