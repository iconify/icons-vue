<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ralt7bb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ralt7bb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:kagi-map" /></template>
