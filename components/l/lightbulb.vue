<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvxdfup1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="qvxdfup1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lightbulb" /></template>
