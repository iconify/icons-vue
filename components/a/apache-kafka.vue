<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-jg9iuni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-jg9iuni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-kafka" /></template>
