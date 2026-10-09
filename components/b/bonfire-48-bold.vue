<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6mc35b_l.css';
import '../../css/o/ofxcalb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6mc35b_l"/><path class="ofxcalb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bonfire-48-bold" /></template>
