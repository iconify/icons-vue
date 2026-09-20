<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp5rq0-5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp5rq0-5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haus-dark" /></template>
