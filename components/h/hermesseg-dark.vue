<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc8abfzvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc8abfzvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermesseg-dark" /></template>
