<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/ua-z8vb0h.css';
import '../../css/l/lewr2fakh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLQJvNbzm"><g class="v3_i3wktz"><path class="ua-z8vb0h"/><path class="lewr2fakh"/></g></mask></defs><path mask="url(#SVGLQJvNbzm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-text-left-one" /></template>
