<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le7bgtmct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":488};
const content = `<path class="le7bgtmct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:facebook" /></template>
