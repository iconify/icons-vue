<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4yi8cb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4yi8cb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-smile" /></template>
