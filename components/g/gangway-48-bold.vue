<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt1i9cb7l.css';
import '../../css/x/xf50wgb4t.css';
import '../../css/t/tb4njgoat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xt1i9cb7l"/><path class="xf50wgb4t"/><path class="tb4njgoat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gangway-48-bold" /></template>
