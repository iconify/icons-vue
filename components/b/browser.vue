<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2b3f1bel.css';
import '../../css/c/ck24u80vm.css';
import '../../css/o/o4r4jf9kc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4VTLgKKc"><g class="ft5dv1b6b"><path class="n2b3f1bel"/><path class="ck24u80vm"/><path clip-rule="evenodd" class="o4r4jf9kc"/></g></mask></defs><path mask="url(#SVG4VTLgKKc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:browser" /></template>
