<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n391m53ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n391m53ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:compass" /></template>
