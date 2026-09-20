<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0vr9-v0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0vr9-v0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logtide-dark" /></template>
