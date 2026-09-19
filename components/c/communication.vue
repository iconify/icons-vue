<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/g/gr941wbsm.css';
import '../../css/s/s1axx0b3q.css';
import '../../css/t/tmslae69u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr0AUwubg"><g class="hv130ab-t"><path class="gr941wbsm"/><path class="s1axx0b3q"/><path class="tmslae69u"/></g></mask></defs><path mask="url(#SVGr0AUwubg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:communication" /></template>
