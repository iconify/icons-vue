<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_a4ygk1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y_a4ygk1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:eject-solid" /></template>
