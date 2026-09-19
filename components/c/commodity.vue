<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fe8ov1blm.css';
import '../../css/n/ny-0gfb3p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8xZFKcWH"><g class="ufeehvblu"><path class="fe8ov1blm"/><path class="ny-0gfb3p"/></g></mask></defs><path mask="url(#SVG8xZFKcWH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:commodity" /></template>
