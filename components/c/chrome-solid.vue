<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-z0-pb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-z0-pb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chrome-solid" /></template>
