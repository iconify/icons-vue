<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/a8qmqgb6k.css';
import '../../css/s/snibgdcaa.css';
import '../../css/t/tmf9e1o6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8qmqgb6k"/><path class="snibgdcaa"/><path class="tmf9e1o6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-sparkles-sharp-two-tone" /></template>
