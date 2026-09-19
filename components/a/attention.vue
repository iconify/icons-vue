<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqx9rpnoy.css';
import '../../css/d/dvqj1jbdf.css';
import '../../css/g/g8s4idbev.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkYaseeMx"><g class="ft5dv1b6b"><path class="mqx9rpnoy"/><path clip-rule="evenodd" class="dvqj1jbdf"/><path class="g8s4idbev"/></g></mask></defs><path mask="url(#SVGkYaseeMx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:attention" /></template>
