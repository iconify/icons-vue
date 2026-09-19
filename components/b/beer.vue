<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/i/igjrdzbaq.css';
import '../../css/t/tv5ukobod.css';
import '../../css/x/xvy4agd9u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5ulH7bQf"><g class="hv130ab-t"><path class="igjrdzbaq"/><path class="tv5ukobod"/><path class="xvy4agd9u"/></g></mask></defs><path mask="url(#SVG5ulH7bQf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:beer" /></template>
