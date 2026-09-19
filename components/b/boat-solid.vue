<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-5n26b9h.css';
import '../../css/w/w593__bmu.css';
import '../../css/m/m0t7g9b_y.css';
import '../../css/v/vgr0ff2tl.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 m-5n26b9h"/><path class="clr-i-solid clr-i-solid-path-2 w593__bmu"/><path class="clr-i-solid clr-i-solid-path-3 m0t7g9b_y"/><path class="clr-i-solid clr-i-solid-path-4 vgr0ff2tl"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:boat-solid" /></template>
