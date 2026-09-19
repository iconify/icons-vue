<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/g/gbh1v2c4l.css';
import '../../css/c/cjud57b0f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyhYEWbVW"><g class="rohhhzb0l"><path class="gbh1v2c4l"/><path class="cjud57b0f"/></g></mask></defs><path mask="url(#SVGyhYEWbVW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:compass-one" /></template>
