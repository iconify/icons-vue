<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzwhn-bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="kzwhn-bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-clear-all" /></template>
