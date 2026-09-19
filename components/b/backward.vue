<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li-6-8xig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="li-6-8xig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:backward" /></template>
