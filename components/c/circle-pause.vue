<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo95jm1am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bo95jm1am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-pause" /></template>
