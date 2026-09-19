<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/x/xxb39ebcb.css';
import '../../css/r/rmado5b8p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA3zqNG0A"><g class="hv130ab-t"><path clip-rule="evenodd" class="xxb39ebcb"/><path class="rmado5b8p"/></g></mask></defs><path mask="url(#SVGA3zqNG0A)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:inner-shadow-up" /></template>
