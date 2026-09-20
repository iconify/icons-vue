<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xia6zebwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xia6zebwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:library" /></template>
