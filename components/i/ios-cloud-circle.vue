<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvi9l7iyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvi9l7iyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-circle" /></template>
