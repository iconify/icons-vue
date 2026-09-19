<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7izo3bwm.css';
import '../../css/u/u0rxo8b_a.css';
import '../../css/e/es5-wygbb.css';
import '../../css/t/tkfqaibra.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGPIhHeQQ"><g class="ft5dv1b6b"><path class="h7izo3bwm"/><path class="u0rxo8b_a"/><path class="es5-wygbb"/><path class="tkfqaibra"/></g></mask></defs><path mask="url(#SVGGPIhHeQQ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:headset" /></template>
