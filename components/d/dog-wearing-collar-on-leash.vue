<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7-32nbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q7-32nbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-wearing-collar-on-leash" /></template>
