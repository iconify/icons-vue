<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twd58db8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="twd58db8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:check-badge" /></template>
