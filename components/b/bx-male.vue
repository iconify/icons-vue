<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfz3w9lrl.css';
import '../../css/v/v8_9c9byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="v8_9c9byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-male" /></template>
