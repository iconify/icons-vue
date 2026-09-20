<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiq-yuotc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="tiq-yuotc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:arrow-up" /></template>
