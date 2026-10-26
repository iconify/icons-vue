<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btc2bc1ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="btc2bc1ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:fire" /></template>
