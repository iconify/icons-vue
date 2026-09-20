<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmj1jdbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cmj1jdbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-ticket-in-slot" /></template>
