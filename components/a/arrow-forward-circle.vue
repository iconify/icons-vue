<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0jjceb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0jjceb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-forward-circle" /></template>
