<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw0b-1bmv.css';
import '../../css/w/wh-70pu7h.css';
import '../../css/d/d788uf64t.css';
import '../../css/o/oe3oz-bur.css';
import '../../css/a/amcescb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hw0b-1bmv"/><path class="wh-70pu7h"/><path class="d788uf64t"/><path class="oe3oz-bur"/><path class="amcescb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-sound" /></template>
