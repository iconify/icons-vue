<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt2oi8v1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vt2oi8v1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-down-circle-solid" /></template>
