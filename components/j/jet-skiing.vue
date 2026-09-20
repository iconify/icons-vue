<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cstzu4b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="cstzu4b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:jet-skiing" /></template>
