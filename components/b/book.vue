<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/axvwh0bez.css';
import '../../css/c/cczcib67m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEDpbBe5z"><g class="v3_i3wktz"><path class="axvwh0bez"/><path clip-rule="evenodd" class="cczcib67m"/></g></mask></defs><path mask="url(#SVGEDpbBe5z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:book" /></template>
