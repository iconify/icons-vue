<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_i801t3n.css';
import '../../css/l/l2d53np2e.css';
import '../../css/v/vnqx6r6he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":151,"height":170,"left":-57.38,"top":-64.6};
const content = `<path class="r_i801t3n"/><path class="l2d53np2e"/><path class="vnqx6r6he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hero-motocorp" /></template>
