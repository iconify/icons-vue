<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8745cjvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8745cjvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kontoj-light" /></template>
