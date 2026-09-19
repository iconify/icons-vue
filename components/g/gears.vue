<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veb_vob-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":962};
const content = `<path class="veb_vob-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gears" /></template>
