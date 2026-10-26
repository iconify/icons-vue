<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpctkhcgf.css';
import '../../css/c/cpnat3u3d.css';
import '../../css/b/b14djybkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":402,"height":100};
const content = `<path clip-rule="evenodd" class="xpctkhcgf"/><path class="cpnat3u3d"/><path class="b14djybkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mage-ai" /></template>
