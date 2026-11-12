<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyu4b0bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyu4b0bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:altcha-dark" /></template>
