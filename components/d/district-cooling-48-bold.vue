<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0vjlubbx.css';
import '../../css/f/fp390_55c.css';
import '../../css/e/e7e9eebcd.css';
import '../../css/f/f5it5obaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r0vjlubbx"/><path class="fp390_55c"/><path class="e7e9eebcd"/><path class="f5it5obaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-cooling-48-bold" /></template>
