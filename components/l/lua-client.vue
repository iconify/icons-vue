<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9sroks9g.css';
import '../../css/s/s4lttrqws.css';
import '../../css/w/wzn6zhbvq.css';
import '../../css/t/tu54racff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9sroks9g"/><g class="s4lttrqws"><path class="wzn6zhbvq"/><path class="tu54racff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:lua-client" /></template>
