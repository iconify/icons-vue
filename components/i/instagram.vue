<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8xyuzbbe.css';
import '../../css/n/nha8y7oaq.css';
import '../../css/m/mp4ag1boz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGy4YSvdBO"><g class="ft5dv1b6b"><path class="h8xyuzbbe"/><path class="nha8y7oaq"/><path class="mp4ag1boz"/></g></mask></defs><path mask="url(#SVGy4YSvdBO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:instagram" /></template>
