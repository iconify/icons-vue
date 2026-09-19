<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvvlq2bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pvvlq2bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleg" /></template>
