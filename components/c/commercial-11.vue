<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2h60z5xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w2h60z5xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:commercial-11" /></template>
