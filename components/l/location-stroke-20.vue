<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oanunl3eu.css';
import '../../css/l/l42y8cc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oanunl3eu"/><path class="l42y8cc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:location-stroke-20" /></template>
