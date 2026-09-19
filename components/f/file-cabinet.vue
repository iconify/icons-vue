<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fv27g2bcl.css';
import '../../css/o/o97bhjbta.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG09G3yFvg"><g class="s9cl3zbei"><path class="fv27g2bcl"/><path class="o97bhjbta"/></g></mask></defs><path mask="url(#SVG09G3yFvg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-cabinet" /></template>
