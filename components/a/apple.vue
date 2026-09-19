<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mi0k_11hx.css';
import '../../css/i/iv3qwd63l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7N9zCtBw"><g class="ft5dv1b6b"><path class="mi0k_11hx"/><path class="iv3qwd63l"/></g></mask></defs><path mask="url(#SVG7N9zCtBw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:apple" /></template>
