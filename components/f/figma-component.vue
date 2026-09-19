<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98f580tp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGc84LZbFk"><path class="k98f580tp"/></mask></defs><path mask="url(#SVGc84LZbFk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:figma-component" /></template>
