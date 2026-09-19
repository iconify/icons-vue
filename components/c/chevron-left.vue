<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v12-rwbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":160,"height":384};
const content = `<path class="v12-rwbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chevron-left" /></template>
