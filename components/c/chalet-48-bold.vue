<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrnno4lpy.css';
import '../../css/q/qr4uhui_c.css';
import '../../css/f/fk2gskbbg.css';
import '../../css/v/v0e3hepfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrnno4lpy"/><path class="qr4uhui_c"/><path class="fk2gskbbg"/><path class="v0e3hepfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chalet-48-bold" /></template>
