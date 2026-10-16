<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brf4rlr5x.css';
import '../../css/n/nd0pwk2rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="brf4rlr5x"/><path class="nd0pwk2rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kerbside-charger-48-bold" /></template>
