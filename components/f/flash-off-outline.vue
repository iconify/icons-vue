<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fttz-rbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fttz-rbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flash-off-outline" /></template>
