<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k9u5bx9ll.css';
import '../../css/q/q0fujjtaq.css';
import '../../css/c/ch12h9bms.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCCgtcd5Q"><g class="ft5dv1b6b"><rect class="k9u5bx9ll"/><path class="q0fujjtaq"/><path class="ch12h9bms"/></g></mask></defs><path mask="url(#SVGCCgtcd5Q)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-working-one" /></template>
