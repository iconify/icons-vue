<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqh6kfb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rqh6kfb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-outline" /></template>
