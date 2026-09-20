<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wksg6tbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wksg6tbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-fill" /></template>
