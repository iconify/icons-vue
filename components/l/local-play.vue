<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9jr4hbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="a9jr4hbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-play" /></template>
