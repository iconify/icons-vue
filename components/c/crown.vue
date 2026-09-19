<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9e5wubrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="e9e5wubrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:crown" /></template>
