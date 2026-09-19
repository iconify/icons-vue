<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/a/aoaqowbnh.css';
import '../../css/f/fmzg4fbof.css';
import '../../css/e/eep_kvb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="aoaqowbnh"/><path class="fmzg4fbof"/><path class="eep_kvb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:beer" /></template>
