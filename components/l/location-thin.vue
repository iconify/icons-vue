<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s96df4b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s96df4b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:location-thin" /></template>
