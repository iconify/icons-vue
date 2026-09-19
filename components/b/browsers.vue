<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_y91mlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="it_y91mlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:browsers" /></template>
