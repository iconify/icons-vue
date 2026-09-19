<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw0ouac-i.css';
import '../../css/g/g6gzcks7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rw0ouac-i"/><path class="g6gzcks7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-earth-alt" /></template>
