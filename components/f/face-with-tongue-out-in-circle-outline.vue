<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qip7rlb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qip7rlb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:face-with-tongue-out-in-circle-outline" /></template>
