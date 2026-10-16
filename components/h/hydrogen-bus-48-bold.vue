<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bym0aibji.css';
import '../../css/u/uo9vznb2b.css';
import '../../css/l/lydypnbam.css';
import '../../css/g/gm44-xbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bym0aibji"/><path class="uo9vznb2b"/><path class="lydypnbam"/><path class="gm44-xbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-bus-48-bold" /></template>
