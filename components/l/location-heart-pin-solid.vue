<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8r6-nb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f8r6-nb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:location-heart-pin-solid" /></template>
