<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7lq3lb7h.css';
import '../../css/r/r6ftfpblh.css';
import '../../css/p/poun__plh.css';
import '../../css/f/fttjgy5uy.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 y7lq3lb7h"/><path class="clr-i-outline clr-i-outline-path-2 r6ftfpblh"/><path class="clr-i-outline clr-i-outline-path-3 poun__plh"/><path class="clr-i-outline clr-i-outline-path-4 fttjgy5uy"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:capacitor-line" /></template>
