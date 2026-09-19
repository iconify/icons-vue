<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g4rirbcmo.css';
import '../../css/u/u3e_2wb-h.css';
import '../../css/z/z284ub4xi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGY8N6Iblf"><g class="ufeehvblu"><path class="g4rirbcmo"/><path class="u3e_2wb-h"/><path class="z284ub4xi"/></g></mask></defs><path mask="url(#SVGY8N6Iblf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:game" /></template>
