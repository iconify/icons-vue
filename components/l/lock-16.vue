<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esama2bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="esama2bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:lock-16" /></template>
