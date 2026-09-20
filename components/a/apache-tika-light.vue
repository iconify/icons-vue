<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adiyfh9-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adiyfh9-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tika-light" /></template>
