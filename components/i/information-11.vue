<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxs5963tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="hxs5963tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:information-11" /></template>
