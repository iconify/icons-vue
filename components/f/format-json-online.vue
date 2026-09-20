<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wur179bzw.css';
import '../../css/u/ujj8k5bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="wur179bzw"/><path class="ujj8k5bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:format-json-online" /></template>
