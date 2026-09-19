<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7smeqbeh.css';
import '../../css/v/va27ux4ej.css';
import '../../css/t/tsepx-fqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y7smeqbeh"/><path class="va27ux4ej"/><path class="tsepx-fqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chat-operational" /></template>
