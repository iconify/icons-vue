<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzdprih6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzdprih6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coursera-dark" /></template>
