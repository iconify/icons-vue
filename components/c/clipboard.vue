<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jsspaw5ps.css';
import '../../css/e/e6j8h5b3s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgpjYybXi"><g class="v3_i3wktz"><path class="jsspaw5ps"/><path class="e6j8h5b3s"/></g></mask></defs><path mask="url(#SVGgpjYybXi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:clipboard" /></template>
