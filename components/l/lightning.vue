<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq-pvm52u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="mq-pvm52u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:lightning" /></template>
