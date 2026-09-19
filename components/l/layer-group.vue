<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9cvk473l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9cvk473l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:layer-group" /></template>
