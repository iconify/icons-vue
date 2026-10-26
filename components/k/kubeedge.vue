<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egx_p66ba.css';
import '../../css/h/h8oeuuwmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":367.64,"height":360.14,"left":-3.82,"top":-0.07};
const content = `<path class="egx_p66ba"/><path class="h8oeuuwmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kubeedge" /></template>
