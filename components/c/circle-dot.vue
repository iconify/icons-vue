<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr9kdcb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yr9kdcb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-dot" /></template>
