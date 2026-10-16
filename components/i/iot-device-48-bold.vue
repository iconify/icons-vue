<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gphkpac7l.css';
import '../../css/c/cwzf0sb5m.css';
import '../../css/p/poayr0wpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gphkpac7l"/><path class="cwzf0sb5m"/><path class="poayr0wpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iot-device-48-bold" /></template>
