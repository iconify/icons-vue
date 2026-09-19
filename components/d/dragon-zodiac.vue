<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sgo8x6bpg.css';
import '../../css/b/b685dd70v.css';
import '../../css/h/h924rebcs.css';
import '../../css/v/v0m5xdb6q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="ipSDragonZodiac0"><g class="ft5dv1b6b"><g clip-path="url(#ipSDragonZodiac1)" class="sgo8x6bpg"><path class="b685dd70v"/><path class="h924rebcs"/></g><defs><clipPath id="ipSDragonZodiac1"><path class="v0m5xdb6q"/></clipPath></defs></g></mask><path mask="url(#ipSDragonZodiac0)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:dragon-zodiac" /></template>
