<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvik0bc0p.css';
import '../../css/c/c2b841tai.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 wvik0bc0p"/><path class="c2b841tai clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:export-solid" /></template>
