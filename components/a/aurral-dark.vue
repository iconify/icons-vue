<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmw-8wbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmw-8wbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aurral-dark" /></template>
