<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfvra_tsh.css';
import '../../css/m/maw6_-12u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<defs><mask id="SVG5B2KGOku"><path class="gfvra_tsh"/></mask></defs><path mask="url(#SVG5B2KGOku)" class="maw6_-12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bottom-bar-one" /></template>
