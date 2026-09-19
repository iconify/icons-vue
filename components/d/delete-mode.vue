<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7g8vpbdo.css';
import '../../css/n/n1986m9oo.css';
import '../../css/b/bag1lsb2k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmYYACbtd"><g class="l7g8vpbdo"><path class="n1986m9oo"/><path class="bag1lsb2k"/></g></mask></defs><path mask="url(#SVGmYYACbtd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:delete-mode" /></template>
