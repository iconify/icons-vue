<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odyw2fb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odyw2fb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-down-right" /></template>
