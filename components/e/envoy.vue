<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt1vj9bim.css';
import '../../css/m/mi5_bgb0n.css';
import '../../css/n/nxeppyb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pt1vj9bim"/><path class="mi5_bgb0n"/><path class="nxeppyb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:envoy" /></template>
