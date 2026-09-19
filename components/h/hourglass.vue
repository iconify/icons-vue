<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf4n8dbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bf4n8dbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:hourglass" /></template>
