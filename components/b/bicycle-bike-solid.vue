<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixim8hiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cixim8hiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bicycle-bike-solid" /></template>
