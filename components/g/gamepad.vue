<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcoduql6c.css';
import '../../css/r/rdd3p3upc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcoduql6c"/><path class="rdd3p3upc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:gamepad" /></template>
