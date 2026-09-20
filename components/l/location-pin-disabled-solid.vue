<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbs3igb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fbs3igb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:location-pin-disabled-solid" /></template>
