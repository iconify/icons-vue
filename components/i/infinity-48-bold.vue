<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qww9sz6vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qww9sz6vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infinity-48-bold" /></template>
