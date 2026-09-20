<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4y_4tbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4y_4tbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hpe-aruba-light" /></template>
