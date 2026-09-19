<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_2i8ot7h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUuGtqhHU"><path class="o_2i8ot7h"/></mask></defs><path mask="url(#SVGUuGtqhHU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:five-five" /></template>
