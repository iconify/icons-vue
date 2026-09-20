<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t37u2kbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t37u2kbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-envelope-in-slot" /></template>
