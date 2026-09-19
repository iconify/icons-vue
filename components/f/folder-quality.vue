<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrso7y3c.css';
import '../../css/s/sz6vb1uxi.css';
import '../../css/y/y04qg5bxg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYjSiaecR"><g class="ylrso7y3c"><path class="sz6vb1uxi"/><path class="y04qg5bxg"/></g></mask></defs><path mask="url(#SVGYjSiaecR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-quality" /></template>
