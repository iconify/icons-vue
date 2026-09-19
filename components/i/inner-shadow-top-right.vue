<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/x/xxb39ebcb.css';
import '../../css/z/zdb0eub1w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSpOiqdNg"><g class="hv130ab-t"><path clip-rule="evenodd" class="xxb39ebcb"/><path class="zdb0eub1w"/></g></mask></defs><path mask="url(#SVGSpOiqdNg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:inner-shadow-top-right" /></template>
