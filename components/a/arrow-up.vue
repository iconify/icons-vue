<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrqn5eb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nrqn5eb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:arrow-up" /></template>
