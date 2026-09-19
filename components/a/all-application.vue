<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccwttzbnx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8LN7BDzz"><path class="ccwttzbnx"/></mask></defs><path mask="url(#SVG8LN7BDzz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:all-application" /></template>
