<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcz4m5c4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<circle class="kcz4m5c4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:circle-filled" /></template>
