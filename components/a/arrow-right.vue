<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae1tb3ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ae1tb3ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-right" /></template>
