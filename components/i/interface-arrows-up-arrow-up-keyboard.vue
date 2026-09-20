<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6kox_6dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l6kox_6dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-up-arrow-up-keyboard" /></template>
