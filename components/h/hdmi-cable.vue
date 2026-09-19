<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/r0fr59bon.css';
import '../../css/i/i69v71bja.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYlJ9KcbF"><g class="aql7dnt-u"><path class="r0fr59bon"/><path class="i69v71bja"/></g></mask></defs><path mask="url(#SVGYlJ9KcbF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hdmi-cable" /></template>
