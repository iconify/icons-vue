<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrso7y3c.css';
import '../../css/s/sz6vb1uxi.css';
import '../../css/r/rl8ffo9dv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGg5PKXbTW"><g class="ylrso7y3c"><path class="sz6vb1uxi"/><path class="rl8ffo9dv"/></g></mask></defs><path mask="url(#SVGg5PKXbTW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-protection" /></template>
