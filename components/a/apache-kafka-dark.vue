<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em5st3bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="em5st3bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-kafka-dark" /></template>
