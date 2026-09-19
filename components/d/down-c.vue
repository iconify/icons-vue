<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/t/thxn9_4aw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9amKGc8o"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="thxn9_4aw"/></g></mask></defs><path mask="url(#SVG9amKGc8o)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:down-c" /></template>
