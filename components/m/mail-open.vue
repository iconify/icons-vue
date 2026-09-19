<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hihlctbwv.css';
import '../../css/h/hvzd0ubol.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz8UWde7M"><g class="v3_i3wktz"><path class="hihlctbwv"/><path class="hvzd0ubol"/></g></mask></defs><path mask="url(#SVGz8UWde7M)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mail-open" /></template>
