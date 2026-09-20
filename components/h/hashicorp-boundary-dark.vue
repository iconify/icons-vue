<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3rfa6bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3rfa6bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-boundary-dark" /></template>
