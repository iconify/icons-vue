<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ai3q1cw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIRubIbDG"><path class="q9ai3q1cw"/></mask></defs><path mask="url(#SVGIRubIbDG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-five" /></template>
