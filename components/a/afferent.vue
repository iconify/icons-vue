<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/h/h9swcnbvp.css';
import '../../css/n/nrodidd9m.css';
import '../../css/o/osaqrz5kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="h9swcnbvp"/><path class="nrodidd9m"/><path class="osaqrz5kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:afferent" /></template>
