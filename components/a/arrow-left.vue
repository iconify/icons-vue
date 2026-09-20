<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyb-4acmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="qyb-4acmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-left" /></template>
